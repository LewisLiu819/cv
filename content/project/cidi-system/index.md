---
title: CIDI电子化问卷系统
summary: 基于PostgreSQL和FSM引擎的动态心理健康问卷系统，提供智能跳转逻辑和高效数据分析能力。
tags:
  - 数据库
  - PostgreSQL
  - 后端开发
  - Web应用
date: '2025-01-01'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: CIDI系统架构
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

CIDI（Composite International Diagnostic Interview）电子化问卷系统是一个专为心理健康评估设计的动态问卷平台，旨在将传统纸质问卷转化为智能化、交互式的数字工具。

## 技术实现

### 数据库设计
- 采用**PostgreSQL**设计五表结构：Question / Edge / Interview / Answer / Context
- 使用**JSONB + GIN/BTREE**索引优化复杂查询性能
- 实现高效的数据存储和检索机制

### 后端开发
- 基于**FSM（有限状态机）引擎**（python-statemachine）实现问卷跳转逻辑
- 使用**FastAPI**构建高性能RESTful API
- 实现问卷动态生成、条件跳转和实时数据验证

### 前端界面
- 采用**React + TypeScript**开发响应式用户界面
- 实现上下文追踪与实时交互功能
- 提供直观的数据可视化和结果展示

## 应用场景

- 心理健康评估与诊断
- 临床研究数据收集
- 远程心理健康筛查
- 长期心理状态监测

## 创新点

- 动态问卷生成：根据用户回答自动调整后续问题
- 高效数据分析：优化的数据库结构支持复杂查询和统计分析
- 多平台兼容：支持Web、移动设备和平板电脑
- 数据安全：符合医疗数据隐私保护标准 