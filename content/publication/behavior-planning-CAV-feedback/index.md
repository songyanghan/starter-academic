---
title: "Behavior Planning For Connected Autonomous Vehicles Using Feedback Deep Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Fei Miao

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *Quantum Information Processing *
publication_short: In *arXiv*

abstract: With the development of communication technologies, con- nected autonomous vehicles (CAVs) can share information with each other. We propose a novel behavior planning method for CAVs to decide actions such as whether to change lane or keep lane based on the observation and shared in- formation from neighbors, and to make sure that there ex- ist corresponding control maneuvers such as acceleration and steering angle to guarantee the safety of each individual au- tonomous vehicle. We formulate this problem as a hybrid partially observable Markov decision process (HPOMDP) to consider objectives such as improving traffic flow efficiency and driving comfort and safety requirements. The discrete state transition is determined by the proposed feedback deep Q-learning algorithm using the feedback action from an un- derlying controller based on control barrier functions. The feedback deep Q-learning algorithm we design aims to solve the critical challenge of reinforcement learning (RL) in a physical system: guaranteeing the safety of the system while the RL is exploring the action space to increase the reward. We prove that our method renders a forward invariant safe set for the continuous state physical dynamic model of the sys- tem while the RL agent is learning. In experiments, our be- havior planning method can increase traffic flow and driving comfort compared with the intelligent driving model (IDM). We also validate that our method maintains safety during the learning process.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- learning-and-control-for-connected-autonomous-vehicles

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

---
