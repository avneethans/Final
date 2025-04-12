---
layout: splash
title: "Welcome to Avneet Hans’ Portfolio"
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: assets/images/background.jpeg
  actions:
    - label: "View My Work"
      url: "#feature"
      class: "btn btn--primary"
excerpt: >
  This site showcases my work in kinesiology, combining data analysis, creative media, and movement science. It serves as a living resume, highlighting skills in Excel, Python, game design, and video analysis.

feature_row:
  - image_path: /assets/images/excel.png
    title: "Data Analysis"
    excerpt: "Performance data analysis"
    url: /excel/
    btn_label: "View"
    btn_class: "btn--primary"

  - image_path: /assets/images/scratch.png
    title: "Scratch Maze"
    excerpt: "Game design & logic"
    url: /scratch/
    btn_label: "Play"
    btn_class: "btn--primary"

  - image_path: /assets/images/video.png
    title: "Video Analysis"
    excerpt: "Sport movement breakdown"
    url: /video/
    btn_label: "Watch"
    btn_class: "btn--primary"

  - image_path: /assets/images/about.png
    title: "About Me"
    excerpt: "A little bit about myself"
    url: /about/
    btn_label: "View"
    btn_class: "btn--primary"
---

<div id="feature">
{% include feature_row %}
</div>
