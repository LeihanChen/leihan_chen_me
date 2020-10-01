---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-range conditional random field for classifying railway electrification system objects using mobile laser scanning data"
authors: ["Jaewook Jung", "Leihan Chen", "Gunho Sohn", "Chao Luo", "Jong-Un Won"]
date: 2016-12-10
doi: "10.3390/rs8121008"

# Schedule page publish date (NOT publication's date).
publishDate: 2016-12-01T22:11:49+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "***Remote Sensing***, 8(12), 1008"
publication_short: ""

abstract: "Railways have been used as one of the most crucial means of transportation in public mobility and economic development. For safe railway operation, the electrification system in the railway infrastructure, which supplies electric power to trains, is an essential facility for stable train operation. Due to its important role, the electrification system needs to be rigorously and regularly inspected and managed. This paper presents a supervised learning method to classify Mobile Laser Scanning (MLS) data into ten target classes representing overhead wires, movable brackets and poles, which are key objects in the electrification system. In general, the layout of the railway electrification system shows strong spatial regularity relations among object classes. The proposed classifier is developed based on Conditional Random Field (CRF), which characterizes not only labeling homogeneity at short range, but also the layout compatibility between different object classes at long range in the probabilistic graphical model. This multi-range CRF model consists of a unary term and three pairwise contextual terms. In order to gain computational efficiency, MLS point clouds are converted into a set of line segments to which the labeling process is applied. Support Vector Machine (SVM) is used as a local classifier considering only node features for producing the unary potentials of the CRF model. As the short-range pairwise contextual term, the Potts model is applied to enforce a local smoothness in the short-range graph; while long-range pairwise potentials are designed to enhance the spatial regularities of both horizontal and vertical layouts among railway objects. We formulate two long-range pairwise potentials as the log posterior probability obtained by the naive Bayes classifier. The directional layout compatibilities are characterized in probability look-up tables, which represent the co-occurrence rate of spatial relations in the horizontal and vertical directions. The likelihood function is formulated by multivariate Gaussian distributions. In the proposed multi-range CRF model, the weight parameters to balance four sub-terms are estimated by applying the Stochastic Gradient Descent (SGD). The results show that the proposed multi-range CRF can effectively classify individual railway elements, representing an average recall of 97.66% and an average precision of 97.07% for all classes."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Conditional Random Field", "Point Cloud", "Railway Tracking"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Published Version
  url: "https://doi.org/10.3390/rs8121008"
- name: Full Text
  url: "https://www.mdpi.com/2072-4292/8/12/1008/htm"
- name: Co-first Author
  url: ""

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
