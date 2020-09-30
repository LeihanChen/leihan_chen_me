---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SIMULATION-BASED DATA AUGMENTATION USING PHYSICAL PRIORS FOR NOISE FILTERING DEEP NEURAL NETWORK"
authors: ["Maryam Jameela", "Leihan Chen", Andrew Sit", "Jacon Yoo", "Chris Verheggen", "Gunho Sohn"]
date: 2020-08-12
doi: "10.5194/isprs-archives-XLIII-B2-2020-247-2020"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-01T22:11:49+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "***The International Archives of Photogrammetry, Remote Sensing and Spatial Information Sciences***, 43, pp. 247-254"
publication_short: ""

abstract: "LiDAR (Light Detection and Ranging) mounted with static and mobile vehicles has been rapidly adopted as a primary sensor for mapping natural and built environments for a range of civil and military applications. Recently, technology advancement in electro- optical engineering enables acquiring laser returns at high pulse repetition frequency (PRF) from 100Hz to 2MHz for airborne LiDAR, which leads to an increase in the density of 3D point cloud significantly. Traditional systems with lower PRF had a single pulse-in-air zone (PIA) big enough to avoid a mismatch between pulse pair at the receiver. Modern multiple pulses-in-air (MPIA) technology ensures multiple windows of operational ranges for single flight line and no blind-zones; downside of the technology is projection of atmospheric returns closer to same PIA zone of neighbouring ground points and more likely to be overlapping with objects of interest. These characteristics of noise compromise the quality of the scene and encourage usage of noise filtering neural network as existing filters are not effective. A noise filtering deep neural network requires a considerable volume of the diverse annotated dataset, which is expensive. We developed simulation for data augmentation based on physical priors and Gaussian generative function. Our study compares deep learning networks for noise filtering and shows performance gain on 3D U-Net. Then, we evaluate 3D U-Net for simulation-based data augmentation, which shows an increase in precision and F1-score. We also provide an analysis of the underline spatial distribution of points and their impact on data augmentation, and noise filtering."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Noise Filtering", "Point Cloud", "Simulation", "3D UNet"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Published Version
  url: "https://doi.org/10.5194/isprs-archives-XLIII-B2-2020-247-2020"
- name: Full Text
  url: "https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLIII-B2-2020/247/2020/isprs-archives-XLIII-B2-2020-247-2020.pdf"

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
