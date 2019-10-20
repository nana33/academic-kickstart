---
title: "The improved DnCNN for linear noise attenuation"
authors:
- Yue Zheng
- Yijun Yuan
- Xu Si
date: "2019-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication: In *Source Themes Conference*
# publication_short: In *STC*

abstract: Seismic data are often highly corrupted by different kinds of noise, including linear noise. Therefore, the attenuation of linear noise has been an essential step in seismic data processing. Traditional methods of linear noise suppression are mostly based on the difference of signals and noise in transform domains. However, the application of these traditional methods is limited to some particular assumptions. For this reason, we utilize an algorithm based on denoising convolutional neural network (DnCNN) to attenuate linear noise. DnCNN is proposed to suppress Gaussian noise in images. In term of the characteristics of linear noise, we make some improvements to the original DnCNN, like patch size, convolutional kernel number. Tests on two types of synthetic data both indicate that the improved DnCNN algorithm is capable of linear noise attenuation in the seismic data.

# Summary. An optional shortened abstract.
summary: Seismic data are often highly corrupted by different kinds of noise, including linear noise. We utilize an algorithm based on denoising convolutional neural network (DnCNN) to attenuate linear noise. Tests on two types of synthetic data both indicate that the improved DnCNN algorithm is capable of linear noise attenuation in the seismic data.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: https://github.com/nana33/academic-kickstart/blob/master/content/zh/post/DnCNN/DnCNN.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

