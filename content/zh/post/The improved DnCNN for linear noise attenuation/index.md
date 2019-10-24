---
title: "Linear noise attenuation using an improved DnCNN"
authors:
- Yue Zheng
- Yijun Yuan
- Xu Si
# date: "2015-09-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ["2"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: Linear noise is a type of common interference wave in seismic data. This noise always interferes with seismic data processing and interpretation. Therefore, the removal of linear noise represents an essential step in seismic data  processing. Here, we proposed an improved method based on a denoising convolutional neural network (DnCNN) to attenuate linear noise in seismic data. This method requires no hypothetical conditions for linear noise attenuation. We simply input training data into the neural network to train the network to learn the features of linear noise within the training data, and then, linear noise can be identified in seismic data sets. Finally, denoised data are obtained by subtracting the identified linear noise from raw seismic data. Since training data represent a key component in the DnCNN, we generated numerous pairs of training data points including synthetic and real seismic data to feed the network. Based on the characteristics of linear noise in the seismic data, we modified the original DnCNN by adjusting the patch size, convolutional kernel number, and learning rate. Through network training, the improved DnCNN developed the ability to automatically identify the linear noise from seismic data. We then used synthetic and real seismic data to quantify the performance of the improved DnCNN.

# Summary. An optional shortened abstract.
summary: Linear noise is a type of common interference wave in seismic data. The improved DnCNN can identify linear noise from seismic data automatically. We used synthetic and real seismic data to quantify the performance of the improved DnCNN.

# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
# url_pdf: post/The improved DnCNN for linear noise attenuation/The improved DnCNN for linear noise attenuation.pdf 
# url_code: 'https://github.com/nana33/DnCNN_denoise_linear-noise'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

