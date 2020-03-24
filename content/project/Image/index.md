---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "获奖研究：基于上下文的图像彩色化算法"
summary: "国际论文发表"
authors: [oscar]
tags: [研究项目]
#categories: []
date: 2020-03-24T18:48:13+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## 论文摘要

将灰度图像转化成彩色图像， 它是一个“病态”的过程，目前，主要方法是基于字典，深度卷积神经网（DCNN） 等算法和基于人工交互的半自动方式[1-5]。本文针对现有彩色化算法存在的缺陷，如半自动算法过于需要人力资源， 基于机器学习的自动算法则在计算成本和计算时间上过高等进行了问题的解决。本文在机器学习的基础上,提出了基 于邻域的上下文信息对图像进行训练得到“亮度-灰度-LBP-NLBP”统计人像生成模型；然后利用灰度值，1阶，2阶上 下文的约束求解目标灰色图像像素，对图像进行着色。与已有方法相比，本文在相当快的时间内使用较少的数据资源 且全自动化的实现了一个信服的彩色化的结果，针对人像，本文的着色效果更加自然，具有很好的真实性。综上所述， 本文通过对图像处理的深入研究，将基于局部二值模式的特征应用在图像颜色重构领域，取得了良好的效果，可望在 图像处理这块领域获得广泛的应用。

## Peerplus经验

Oscar: 科研对我来说是一个平台，能分享我对于特定领域知识的发现。这种standing on giant's shoulder and be able to share my new insights with some of the brightest minds in the world的感觉是一般活动所无法体验的。在peer-review的过程中能与教授/同行的交流过程也让我受益深浅。
