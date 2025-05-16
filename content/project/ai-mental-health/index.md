---
title: AI心理健康诊断支持系统
summary: 基于BERT的情感分析与多模态模型，用于辅助PTSD、抑郁、焦虑等精神健康问题的早期筛查与诊断。
tags:
  - 深度学习
  - NLP
  - 医疗健康
  - BERT
date: '2024-01-01'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: AI心理健康诊断系统界面
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: 代码
    url: https://github.com/
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

## 项目概述

AI心理健康诊断支持系统是一个基于深度学习的辅助诊断工具，旨在通过分析用户的文本、语音和面部表情等多模态数据，为心理健康专业人士提供诊断参考。

## 技术实现

- **文本情感分析**：使用预训练的BERT模型对社交媒体文本进行情感分类，基于Sentiment140数据集训练
- **可解释性**：结合K-Fold交叉验证与LIME技术，提供可视化解释，增强模型透明度
- **用户界面**：基于Streamlit构建直观的Web界面，支持实时情感预测与结果可视化
- **多模态扩展**：正在整合语音分析、面部表情识别和动态问卷数据，用于PTSD、抑郁、焦虑等多分类诊断

## 应用场景

该系统可用于心理健康初筛、远程诊断辅助、长期情绪监测等场景，特别适用于医疗资源匮乏地区或需要隐私保护的用户。

## 未来规划

- 扩展数据集，提高多语言支持能力
- 加入时序分析，追踪用户情绪变化趋势
- 开发移动应用，提供随时随地的心理健康监测
- 与专业心理健康机构合作，进行临床验证 