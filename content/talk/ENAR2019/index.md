---
title: An evaluation of machine learning and classical statistical methods for discovery in large-scale translational data
event: Eastern North American Region International Biometric Society Conference 2019
event_url: https://www.enar.org

location: Washington, DC
address:
  street: 
  city: 
  region: 
  postcode: 
  country: 

summary: 2019 beamer slides for ENAR conference.
abstract: "A recent paper in the top journal Nature Methods- Statistics versus machine learning by Bzdok, Altman and Krzywinski - concludes that random forests will correctly identify a greater proportion of truly dysregulated genes more often than traditional methods based on p-value adjustments such as Benjamini-Hochberg. However, the random forests approach, as implemented, requires prior knowledge of the number of true dysregulated genes - information not available in practice. Thus, subsequent conclusions are biased against traditional methods. In related work, second-generation p-values have recently been proposed for large-scale inference. We evaluate the viability and accuracy of this approach as well. Simulation studies of microarray of gene expression data are used. We maintain the original structure proposed by Bzdok, Altman, and Brzywinski. The different methods used to determine the number of dysregulated genes in simulated data were: unadjusted p-values, Benjamini-Hochberg adjusted p-values, random forest importance levels, and second-generation p-values. When all methods are given the same prior information, second-generation p-values generally outperform all other methods. The finding that random forest importance levels via a machine learning algorithm outperform classical methods was not reproduced nor validated in our examination. The choice of an analysis methods for large-scale translation data is critical to the success of any statistical investigation. In this context, machine learning methods fail to outperform standard methods and, given their additional complexity, are not the optimal approach."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-03-10"
date_end: 
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: ""

authors: []
tags:
- Multiple Testing
- Machine Learning

links:
url_pdf: files/Hollister_ENAR.pdf
url_code: 
url_dataset: 
url_poster: 
url_project: 
url_slides: 
url_source: 
url_video: 

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Enable math on this page?
math: true
---

