---
title: "ApproxNet: Content and Contention Aware Video Analytics System for the Edge"
authors:
- Ran Xu
- Jinkyu Koo
- Rakesh Kumar
- Peter Bai
- Subrata Mitra
- admin
- Saurabh Bagchi
date: "2019-08-28T19:29:41Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: In *Source Themes Conference*
#publication_short: In *STC*

abstract: Videos take lot of time to transport over the network, hence running analytics on live video at the edge devices, right where it was captured has become an important system driver. However these edge devices, e.g., IoT devices, surveillance cameras, AR/VR gadgets are resource constrained. This makes it impossible to run state-of-the-art heavy Deep Neural Networks (DNNs) on them and yet provide low and stable latency under various circumstances, such as, changes in the resource availability on the device, the content characteristics, or requirements from the user. In this paper we introduce ApproxNet, a video analytics system for the edge. It enables novel dynamic approximation techniques to achieve desired inference latency and accuracy trade-off under different system conditions and resource contentions, variations in the complexity of the video contents and user requirements. It achieves this by enabling two approximation knobs within a single DNN model, rather than creating and maintaining an ensemble of models (such as in MCDNN [Mobisys-16]). Ensemble models run into memory issues on the lightweight devices and incur large switching penalties among the models in response to runtime changes. We show that ApproxNet can adapt seamlessly at runtime to video content changes and changes in system dynamics to provide low and stable latency for object detection on a video stream. We compare the accuracy and the latency to ResNet [2015], MCDNN, and MobileNets [Google-2017].

# Summary. An optional shortened abstract.
summary: ApproxNet is a video analytics system for the edge. It enables novel dynamic approximation techniques to achieve desired inference latency and accuracy trade-off under different system conditions and resource contentions, variations in the complexity of the video contents and user requirements.

tags:
- Source Themes
featured: true

links:
- name: Demo Video
  url: https://approxnet.github.io/
url_pdf: https://arxiv.org/pdf/1909.02068.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

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
<!-- projects:
- internal-project -->

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
<!-- slides: example -->
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

