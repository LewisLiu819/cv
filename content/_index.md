---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 下载简历
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '🔬 我的研究'
      subtitle: ''
      text: |-
        我目前专注于深度学习与可解释人工智能领域的研究。主要研究兴趣包括：
        
        - 使用BERT等NLP模型对文本进行情感分析
        - 结合LIME等技术提升AI模型的可解释性
        - 开发AI心理健康辅助诊断系统
        - 多模态机器学习在医疗健康领域的应用
        
        欢迎交流与合作 👋
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: 主要项目
      subtitle: 我正在进行的研究和开发项目
      text: ""
      # Filter content to display
      filters:
        folders:
          - project
        featured_only: true
    design:
      columns: '1'
      view: showcase
  - block: markdown
    content:
      title: 'AI心理健康诊断支持系统'
      subtitle: '2024至今'
      text: |-
        - 使用**BERT**对社交媒体文本进行情感分类（Sentiment140数据集）
        - 结合**K-Fold交叉验证**与**LIME**提升模型可解释性
        - 构建**Streamlit**界面，支持实时情感预测与可视化解释
        - 正在扩展**多模态模型**（语音、面部表情、动态问卷数据融合）以实现PTSD、抑郁、焦虑等多分类诊断
    design:
      columns: '2'
  - block: markdown
    content:
      title: 'CIDI电子化问卷系统'
      subtitle: '2025'
      text: |-
        - 设计**PostgreSQL**五表（Question / Edge / Interview / Answer / Context），采用**JSONB + GIN/BTREE**索引优化检索
        - 实现**FSM引擎**（python-statemachine）与**FastAPI**后端，动态控制问卷跳转逻辑
        - 前端使用**React + TypeScript**，实现上下文追踪与实时交互
    design:
      columns: '2'
  - block: markdown
    content:
      title: '教育与领导力'
      subtitle: ''
      text: |-
        ### "COMPSCI 0.10" 小学生计算机科学课程 (2024至今)
        - 课程改编自UC Berkeley CS10，覆盖8个班级、约350名学生
        - 负责课程设计、授课及项目作业指导
        
        ### High School Computer Science Club (创始人&主席, 2023至今)
        - 创立并带领40+成员进行项目开发与算法竞赛培训
        
        ### ACSL (American Computer Science League) 团队队长 (2024)
        - 设计训练计划，带领团队在预赛中取得**满分**成绩
    design:
      columns: '1'
  - block: markdown
    content:
      title: '兴趣爱好'
      subtitle: ''
      text: |-
        - **运动**: 网球（校队，休闲）
        - **音乐**: Hip-hop（Kendrick Lamar, J. Cole, Kanye West, Lil Wayne, Baby Keem）
        - **STEM玩具**: LEGO Technic（Porsche 911, Defender, McLaren F1, Bugatti Chiron, 70-周年纪念卡车）
        - **时尚**: 极简高级混搭；黑色大衣、复古金丝框眼镜；偏好木质香调
    design:
      columns: '1'
  - block: cta-card
    demo: false
    content:
      title: 📅 未来计划
      text: |-
        - 2025年：参加Stanford Summer Session，学习CS106B（Data Structures & Algorithms）与SYMSYS123（Neuroscience & Artificial Intelligence）
        - 2025年：参加AP考试（Calculus BC、Microeconomics、Macroeconomics）
        - 2025-2026年：扩展AI心理健康诊断系统，加入多模态功能
        - 2026年：申请美国大学计算机科学/人工智能专业
      button:
        text: 联系我
        url: 'mailto:your-email@example.com'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
