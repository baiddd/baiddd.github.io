---
permalink: /
title: "Jiachuan BAI — Machine Learning Engineer, Deep Learning for Time-Series & Imaging"
hide_title: true
excerpt: "Jiachuan BAI — Machine Learning Engineer, deep learning for time-series and imaging"
author_profile: true
toc: true
toc_label: "On this page"
toc_icon: "list"
toc_sticky: true
toc_h_max: 2
redirect_from:
  - /about/
  - /about.html
  - /projects/
  - /education/
  - /communications/
---

<div class="intro-bubble">
  <div class="intro-bubble__titlebar">
    <span class="intro-bubble__dot intro-bubble__dot--red"></span>
    <span class="intro-bubble__dot intro-bubble__dot--yellow"></span>
    <span class="intro-bubble__dot intro-bubble__dot--green"></span>
    <span class="intro-bubble__filename">about.md</span>
  </div>
  <div class="intro-bubble__body" markdown="1">
\# From a Master's in Signal and Image Processing to a Ph.D. in Bioinformatics at Institut Pasteur, where I specialized in deep learning-augmented super-resolution microscopy, my journey has been about applying computational tools to biology and medicine.

\# Today, as a Machine Learning Engineer in the health-tech industry, I bring 6+ years of machine learning and deep learning experience: designing algorithms for physiological time-series data and writing them in C/C++ for integration into embedded systems. I'm driven by translating complex data into real-world health impact.
  </div>
</div>

## Experience

{% include base_path %}

{% assign experience_items = site.projects | where: "type", "experience" | reverse %}
{% for post in experience_items %}
  {% include archive-single.html heading_level="h3" %}
{% endfor %}

## Hackathon Projects

<div class="bordered-list" markdown="0">
{% assign hackathon_items = site.projects | where: "type", "hackathon" | reverse %}
{% for post in hackathon_items %}
  {% include archive-single.html heading_level="h3" %}
{% endfor %}
</div>

## Scientific Communication

### Publication

---

Ouyang, W.#, **Bai, J.#**, et al. (2022). ShareLoc — an open platform for sharing localization microscopy data, Nature Methods, 19(11), pp. 1331–1333. (# equal contribution)  [[paper](https://www.nature.com/articles/s41592-022-01659-0)]

Ito, T., **Bai, J**. and Ostry, D.J. (2020). Contribution of sensory memory to speech motor learning, Journal of Neurophysiology, 124(4), pp. 1103–1109. [[paper](https://journals.physiology.org/doi/full/10.1152/jn.00457.2020)]

### Talk

---

[Symposium Artificial Intelligence in Biology and Health - Paris](https://research.pasteur.fr/en/event/symposium-artificial-intelligence-in-biology-and-health/) (2023.07.04)

[Single Molecule Localization Microscopy Symposium 2022 - Paris](https://smlms.org/detailed-program-wednesday-31st-2022/) (2022.08.31)

[3rd Imabio YSN conference, ENS de Lyon](https://sites.google.com/view/iysn/lyon-2022-ysn-conference/program?authuser=0) (2022.07.06)

[2nd meeting of the GDR Architecture and Dynamics of the Nucleus and Genomes, ENS de Lyon](https://www.ens-lyon.fr/en/event/research/gdr-adng-second-annual-meeting) (2022.06.22)

[Department day, Biologie Computationnelle department, Institut Pasteur](https://research.pasteur.fr/fr/event/2021-computational-biology-department-days/) (2021.11.29)

[Seminar WIP (Work In Progress), Cell Biology and Infection Department, Institut Pasteur](#) (2020.12.14)

### Poster

---

[21st International European Light Microscopy Initiative Meeting, Turku](https://elmi2022.eu/)(2022.06.07)

## Education

### **Bio-informatics**, Ph.D.

2023, Complexité du vivant, Sorbonne Université/Institut Pasteur

---

### **Signal Image Processing Methods and Application (SIGMA)**, Master 2

2019, Phelma, Grenoble INP

---

### **Electrical system**, Master 1

2018, Université Grenoble Alpes

---

### **Electronic Engineering and Automation**, Bachelor

2016, Hebei University of Engineering
