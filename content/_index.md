---
title: 'Home'
date: 2025-03-14
type: landing

design:
  spacing: "6rem"

sections:
  # 1) 顶部 Hero 区
  - block: hero
    content:
      title: "华北电力大学重力储能团队"
      text: "致力于推动重力储能技术在新能源电力系统中的深度应用，为绿色低碳转型贡献力量。"
      primary_action:
        text: "了解更多"
        url: "/research-overview/"   # 跳转到团队研究概括页面
        icon: rocket-launch
      secondary_action:
        text: "加入我们"
        url: "/admissions/"          # 跳转到招生指南页面
      announcement:
        text: "欢迎浏览我们的全新官网！"
        link:
          text: "查看最新动态"
          url: "/news/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: ""
      background:
        color: ""
        image:
          filename: ""               # 如有背景图，请将图片上传至 assets/media/ 并在此填写文件名
          filters:
            brightness: 0.5

  # 2) 数据统计区
  - block: stats
    content:
      items:
        - statistic: "50+"
          description: |
            科研项目  
            全国领先
        - statistic: "100+"
          description: |
            高水平论文  
            国际认可
        - statistic: "10+"
          description: |
            企业合作  
            技术转化
    design:
      css_class: "bg-gray-100 dark:bg-gray-800"
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  # 3) 团队优势展示区
  - block: features
    id: features
    content:
      title: "团队优势"
      text: "华北电力大学重力储能团队凭借雄厚的科研实力、跨学科协作和成果转化能力，在重力储能技术领域处于领先地位。我们的优势包括："
      items:
        - name: "技术领先"
          icon: bolt
          description: "拥有先进的储能系统设计、优化控制和智能化运维技术，确保技术始终保持前沿。"
        - name: "跨学科协作"
          icon: users
          description: "集结电气、机械、材料、控制等多领域专家，实现深度融合与创新。"
        - name: "成果转化"
          icon: check-circle
          description: "已在国际顶级期刊和会议发表100余篇论文，申请和授权多项专利，助力产业应用。"
        - name: "丰富资源"
          icon: award
          description: "依托国家重点实验室和多家企业合作，提供充足的科研资金和实践平台。"
    design:
      css_class: ""
      spacing:
        padding: ["2rem", 0, "2rem", 0]

  # 4) CTA 卡片：引导访客了解更多或联系团队
  - block: cta-card
    content:
      title: "期待与您共创未来"
      text: "无论您是科研伙伴、产业合作伙伴，还是有志于深造的学子，华北电力大学重力储能团队都欢迎您的加入。了解我们的研究进展与团队动态，请立即联系我们！"
      button:
        text: "立即联系"
        url: "/contact/"
    design:
      card:
        css_class: "bg-primary-700 text-white"
        css_style: ""
---
