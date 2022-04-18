---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Internship Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: team leader
    company: Beijing Institute of Technology
    company_url: 'https://english.bit.edu.cn/'
    company_logo: org-gc
    location: Beijing
    date_start: '2020-06-01'
    date_end: '2021-09-01'
    description: |2-
        National Undergraduate Training Programs for Innovation and Entrepreneurship in 2020. 
        We applied the Yolov5 algorithm to the OCR field, and used the ICDAR2014 dataset to train a yolo model that can achieve accurate text detection.
        Responsibilities include:
        
        * Organize and lead team members
        * Develop a phased research plan
        * Built the model with pytorch
        
  - title: team member
    company: Beijing Institute of Technology
    company_url: 'https://english.bit.edu.cn/'
    company_logo: org-gc
    location: Beijing
    date_start: '2021-09-01'
    date_end: ''
    description: |2-
        National Undergraduate Training Programs for Innovation and Entrepreneurship in 2021.
        We implemented a model that converts RGB images to Thermal maps on the FLIR dataset using CycleGAN.
        Responsibilities include:
        
        * Read related papers
        * Built the model with pytorch

design:
  columns: '2'
---
