---
title: "Deep learning-based hybrid clinical decision support system algorithm for COVID-19 diagnosis via PCR graphics and Thorax CT images, preliminary data"
authors:
- E B Verdi, M Gok, D Dogan Mülazimoglu, M B Terzi, A Gurun Kaya, S Erol, O İsik, O U Guvendik, C Uzun, A H Elhan, Z C Karahan, A Azap, A Kaya, O Arikan, O Ozdemir Kumbasar

date: "2022-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

# Publication name and optional abbreviated publication name.

abstract: Severe Acute Respiratory Syndrome Coronavirus 2 (SARS-CoV-2) is a global threat impacting the lives of millions of people worldwide. Automated detection of lung infections from Computed Tomography scans represents an excellent alternative; however, segmenting infected regions from CT slices encounters many challenges. Developing a diagnosis system based on deep learning techniques to detect and quantify COVID-19 infection and pneumonia screening using CT imaging. Contrast Limited Adaptive Histogram Equalization pre-processing method was used to remove the noise and intensity in homogeneity. Black slices were also removed to crop only the region of interest containing the lungs. A U-net architecture, based on CNN encoder and CNN decoder approaches, is then introduced for a fast and precise image segmentation to obtain the lung and infection segmentation models. For better estimation of skill on unseen data, a fourfold cross-validation as a resampling procedure has been used. A three-layered CNN architecture, with additional fully connected layers followed by a Softmax layer, was used for classification. Lung and infection volumes have been reconstructed to allow volume ratio computing and obtain infection rate.Starting with the 20 CT scan cases, data has been divided into 70% for the training dataset and 30% for the validation dataset. Experimental results demonstrated that the proposed system archieves a dice score of 0.98 and 0.91 for the lung and infection segmentation tasks, respectively, and an accuracy of 0.98 for the classification task. The proposed workflow aimed at obtaining good performances for the different system’s components, and at the same time, dealing with reduced datasets used for training. # Summary. An optional 

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://erj.ersjournals.com/content/60/suppl_66/1357.article-info'
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
---
