---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: 实习经历
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
  - title: 队长
    company: 北京理工大学
    company_url: 'https://bit.edu.cn/'
    company_logo: bit
    location: 北京市
    date_start: '2020-06-01'
    date_end: '2021-09-01'
    description: |2-
        学校 2020 年大创，应用 Yolov5 算法到 OCR 领域中，用 ICDAR2014 数据集训练出一个能实现准确文字定位的yolo 模型，以此实现 OCR 中的文字定位效果。

        项目中我与导师沟通确定研究方法和思路，负责指定阶段研究计划，并给小组成员分配了任务。通过搜集，阅读相关文献，我对目标识别和 OCR 领域有了基本的认识。在小组成员的共同努力下，我们实现了一个可以考虑到文字旋转角度以及景深的识别模型。

        职务包括:
        
        * 组织并领导队员
        * 制定阶段性研究计划
        * 搭建基于pytorch框架的模型
        
  - title: 队员
    company: 北京理工大学
    company_url: 'https://bit.edu.cn/'
    company_logo: bit
    location: 北京市
    date_start: '2021-09-01'
    date_end: ''
    description: |2-
        学校 2021 年大创，通过使用 CycleGAN 在 FLIR 数据集上实现了一个将 RGB 图像转化为 Thermal 热感图的模型。
        
        项目中我作为队员，阅读了队长提供的相关论文，用 pytorch 搭建了共同讨论的网络模型。实验结果显示模型对于白天黑天的偏差有很强的抗干扰能力，但是会被如雨滴等天气因素导致效果不佳。目前团队尝试在模型结构上进行探索与改良。

        职务包括:
        
        * 阅读相关文献
        * 搭建基于pytorch框架的模型

  - title: 研究员
    company: 北京理工大学
    company_url: 'https://bit.edu.cn/'
    company_logo: bit
    location: 北京市
    date_start: '2021-12-01'
    date_end: ''
    description: |2-
        目标物指代理解(referring expression comprehension)。给定一个自然语言的描述，目标指向理解期望准确地在一张图像中找到描述对应的区域。模型需要对文本和视觉领域来进行联合理解和推理。

        我们尝试实现一个模型，该模型可以在多尺度空间中mask掉图像和自然语言的语义相同部分。项目中我通过阅读相关论文，并积极与导师沟通，确认了我的思路创新点以及可实现性。我做为主要研究人员用 pytorch 搭建了相关模型并进行实验。

        职务包括:
        
        * 阅读相关文献
        * 搭建基于pytorch框架的模型

design:
  columns: '2'
---
