---
title: "Memory based Multi-tasking A3C Agent"
authors:
- admin
date: "2018-12-05"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ["4"]

# Publication name and optional abbreviated publication name.
#publication: In *Source Themes Conference*
#publication_short: In *STC*

abstract: Reinforcement learning agents have been found to be successful in various tasks and have even been transferred to and used in real-world domains. However, there is still a long way to go before they come close to humans when it comes to multi-tasking and transfer learning over similar and vastly different tasks. The idea for our project emerged from the belief that memory storage in cells is one advantage humans possess over machines that results in a significant difference in performance level, especially in data efficiency and long term dependencies between rewards and actions in a Reinforcement learning setup. In this project, we have done an extensive survey on existing methods for multi-tasking and incorporating memory in RL agents, and have developed and deployed a model that has memory and can learn to do multiple tasks. We have demonstrated the performance of our model on single as well as multiple(multi-tasking setup) Atari games, but in theory, the model can be extended to any reinforcement learning problem.

# Summary. An optional shortened abstract.
summary: A memory-incorporated RL framework that can learn to do Multiple tasks through active learning, and effectively reduce catastrophic forgetting on a set of Atari Games.

tags:
- Source Themes
featured: true

links:
#- name: Demo Video
# url: https://approxnet.github.io/
url_pdf: files/MRM-A3C.pdf
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
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

 -->