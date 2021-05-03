---
title: "DeResolver: A Decentralized Negotiation and Conflict Resolution Framework for Smart City Services"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yukun Yuan
- Meiyi Ma
- admin
- Desheng Zhang
- Fei Miao
- John Stankovic
- Shan Lin

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *12th ACM/IEEE International Conference on Cyber-Physical Systems*
publication_short: In *ICCPS (Best paper award finalist)*

abstract: As various smart services are increasingly deployed in modern cities, many unexpected conflicts arise due to various physical world couplings. Existing solutions for conflict resolution often rely on centralized control to enforce predetermined and fixed priorities of different services, which is challenging due to the inconsistent and private objectives of the services. Also, the centralized solutions miss opportunities to more effectively resolve conflicts according to their spatiotemporal locality of the conflicts. To address this issue, we design a decentralized negotiation and conflict resolution framework named DeResolver, which allows services to resolve conflicts by communicating and negotiating with each other to reach a Pareto-optimal agreement autonomously and efficiently. Our design features a two-level semi-supervised learning-based algorithm to predict acceptable proposals and their rankings of each opponent through the negotiation. Our design is evaluated with a smart city case study of three services: intelligent traffic light control, pedestrian service, and environmental control. In this case study, a data-driven evaluation is conducted using a large data set consisting of the GPS locations of 246 surveillance cameras and an automatic traffic monitoring system with more than 3 million records per day to extract real-world vehicle routes. The evaluation results show that our solution achieves much more balanced results, i.e., only increasing the average waiting time of vehicles, the measurement metric of intelligent traffic light control service, by 6.8% while reducing the weighted sum of air pollutant emission, measured for environment control service, by 12.1%, and the pedestrian waiting time, the measurement metric of pedestrian service, by 33.1%, compared to priority-based solution.

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
