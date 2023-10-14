---
title: 'An ecologically-constrained deep learning model for tropical leaf phenology monitoring using PlanetScope satellites'
authors:
  - Jing Wang
  - Guangqin Song
  - Michael Liddell
  - Patricia Morellato
  - Calvin K.F. Lee
  - Dedi Yang
  - Bruna Alberton
  - Matteo Detto
  - Xuanlong Ma 
  - Yingyi Zhao
  - Henry C.H. Yeung
  - Hongsheng Zhang
  - Michael Ng
  - Bruce W. Nelson
  - Alfredo Huete
  - Jin Wu
author_notes:
  - 'a,b,1'
  - 'b,1'
  - 'c'
  - 'd'
  - 'b'
  - 'e'
  - 'd,f'
  - 'g'
  - 'h,i,j'
  - 'b'
  - 'b'
  - 'k,l'
  - 'm'
  - 'n'
  - 'o'
  - 'b,l,*'
date: '2023-05-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Remote Sensing of Environment'
publication_short: 'Remote Sens Environ'

abstract: In tropical forests, leaf phenology signals leaf-on/off status and exhibits considerable variability across scales from a single tree-crown to the entire forest ecosystem. Such phenology signals importantly regulate large-scale biogeochemical cycles and regional climate. PlanetScope CubeSats data with a 3-m resolution and near-daily global coverage provide an unprecedented opportunity to monitor both fine- and ecosystem-scale phenology variability along large environmental gradients. However, a scalable method that accurately characterizes leaf phenology from PlanetScope with biophysically meaningful metrics remains lacking. We developed an index-guided, ecologically constrained autoencoder (IG-ECAE) method to automatically derive a deciduousness metric (percentage of upper tree canopies with leaf-off status within an image pixel) from PlanetScope. The IG-ECAE first estimated the reflectance spectra of leafy/leafless canopies based on their spectral indices characteristics, then used the derived reflectance spectra to guide an autoencoder deep learning method with additional ecological constraints to refine the reflectance spectra, and finally used linear spectral unmixing to estimate the relative abundance of leafless canopies (or deciduousness) per PlanetScope image pixel. We tested the IG-ECAE method at 16 tropical forest sites spanning multiple continents and a large precipitation gradient (1470–2819 mm year−1). Among these sites, we evaluated the PlanetScope-derived deciduousness against corresponding measures derived from WorldView-2 (n = 9 sites) and local phenocams (n = 9 sites). Our results show that PlanetScope-derived deciduousness agrees:1) with that derived from WorldView-2 at the patch level (90 m × 90 m) with r2 = 0.89 across all sites; and 2) with that derived from phenocams to quantify ecosystem-scale seasonality with r2 ranging from 0.62 to 0.96. These results demonstrate the effectiveness and scalability of IG-ECAE in characterizing the wide variability in deciduousness across scales from pixels to forest ecosystems, and from a single date to the full annual cycle, indicating the potential for using high-resolution satellites to track the large-scale phenological patterns and response of tropical forests to climate change.
# Summary. An optional shortened abstract.
summary: 

tags:
  - Tropical forests
  - Carbon cycles
  - Environmental gradient
  - Deciduousness
  - Multi-scale remote sensing
  - Machine learning

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0034425722005351
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
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
slides:
---

