---
title: 'Land Surface phenology retrievals for arid and semi-arid ecosystems'
authors:
  - Qiaoyun Xie
  - Jamie Cleverly 
  - Caitlin E. Moore
  - Yanling Ding
  - Christopher C. Hall
  - XuanlongMa
  - Luke A. Brown
  - Cong Wang
  - Jason Beringer
  - Suzanne M. Prober
  - Craig Macfarlane
  - Wayne S. Meyer
  - Gaofei Yin
  - Alfredo Huete

author_notes:
  - 'a,*'
  - 'a,b'
  - 'c,d'
  - 'a,e,*'
  - 'a'
  - 'f'
  - 'g'
  - 'h'
  - 'c'
  - 'i'
  - 'i'
  - 'j'
  - 'k'
  - 'a,*'

date: '2022-01-21T00:00:00Z'
doi: 'https://doi.org/10.1016/j.isprsjprs.2022.01.017'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-21T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'ISPRS Journal of Photogrammetry and Remote Sensing'
publication_short: 'ISPRS J Photogramm'

abstract: Land surface phenology (LSP) plays a critical role in the regulation of photosynthesis, evapotranspiration, and energy fluxes. Significant progress has been made in extracting LSP information over large areas using satellite data, yet LSP retrievals remain a challenge over vast arid and semi-arid ecosystems because of sparse greenness, high variability and the lack of distinct annual patterns; for example, the MODerate Imaging Spectrometer (MODIS) Land Cover Dynamics Product MCD12Q2 that provides LSP metrics globally often failed to provide LSP information in these ecosystems. In this study, we used a modified threshold algorithm to extract LSP timing metrics, including the start, peak, and end of growing seasons, using the 16-day composite Enhanced Vegetation Index (EVI) time series from MODIS data. We applied this regionally customized algorithm across all arid and semi-arid climate regions of Australia (75% of the continental land area) encompassing shrublands, grasslands, savannas, woodlands, and croplands, extracting LSP metrics annually from 2003 to 2018, with up to two (phenology) seasons accounted for in each year. Our algorithm yielded an average of 64.9% successful rate of retrieval (proportion of pixels with retrieved LSP metrics) across 16 years in Arid and Semi-arid AUStralia (AS-AUS), which was a significant increase compared to the 14.5% rate of retrieval yielded in our study area by the global product and the major cause of the different performances between these two approaches was the different EVI amplitude restrictions utilized to avoid spurious peaks (i.e. EVI amplitude ≥ 0.1 used by the global product and peak EVI ≥ time series average EVI used by our algorithm). Gross primary productivity (GPP) measurements at OzFlux eddy covariance (EC) tower sites were used to cross-compare with the presence/absence of growing seasons detected by our algorithm, and 97% of our retrieved seasons matched with those extracted using EC data. Preliminary tests at five OzFlux sites showed that our algorithm was robust to view angle-induced sensitivity of the input data and showed similar performance when using EVI data calculated using MODIS Nadir BRDF-Adjusted Reflectance product. Our retrieved LSP metrics revealed that vegetation growth in arid ecosystems is highly irregular and can occur at any time of the year, more than once in a year, or can skip a year. The proportion of pixels with two growing seasons was found to be correlated with the average annual precipitation of the study area (p < 0.01), providing an estimation approach of LSP via rainfall. Our study improves the detection and measurement of vegetation phenology in arid and semi-arid regions by improving the spatial extend of LSP retrievals, which contributes to studies on LSP variations and dryland ecosystem resilience to climate change. More evaluation is planned for future work to assess and further improve the accuracy of the retrieved LSP metrics.
# Summary. An optional shortened abstract.
summary: 

tags:
  - Land surface phenology
  - Arid and semi-arid ecosystems
  - EVI
  - MODIS
  - Gross primary productivity
  - TERN OzFlux

featured: false

# links:
# - name: ""
#   url: ""
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

