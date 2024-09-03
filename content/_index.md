---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: background.png
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Hello 你好 👋'
      subtitle: ''
      text: |-
        Chen Yedong is a Ph.D. candidate in Municipal Engineering at China University of Mining and Technology, under the supervision of Professor Chang Jiang. His research focuses on the renewal of mining cities and land use planning, particularly within the framework of compact city concepts. Chen has led research projects funded by the Jiangsu Provincial Graduate Innovation Program and the Future Scientist Program at China University of Mining and Technology, while also participating in several national and local research projects. He has published numerous papers in both domestic and international journals and conferences, and has presented his work at various international academic conferences, receiving widespread recognition.

        In his academic endeavors, Chen has published two SCI-indexed papers and has been awarded for Best Paper and Best Presentation at several international conferences. His research extends beyond academia, contributing to practical projects such as the urban design for the transformation of Fenghuangshan Mine and the development planning for the Xinyi Food Industry Park in Jiangsu. Chen has received multiple honors, including the Excellent Master's Thesis Award in Shandong Province and the first prize in the Yuan Ye Cup International Competition, showcasing his innovation in both research and practical applications.

        陈业东，中国矿业大学市政工程专业博士研究生，师从常江教授。他专注于矿业城市更新与用地布局规划，尤其在紧凑城市理念下的研究方面表现出色。陈业东主持了江苏省研究生创新计划和中国矿业大学未来科学家计划等科研项目，并参与了多个国家级和地方级的科研项目。他在国内外期刊和会议上发表了多篇论文，并多次参与国际学术会议并作报告，其研究成果受到广泛认可。

        在学术研究方面，陈业东已发表SCI论文2篇，并在多项国际会议中获得最佳论文奖和最佳汇报奖。他的研究工作不仅限于学术，还涉及实际项目的规划与设计，如凤凰山矿转型发展城市设计、江苏新沂食品产业园发展规划等。他曾获得山东省优秀硕士学位论文、园冶杯国际竞赛一等奖等多项荣誉，充分展示了他在科研与实践领域的创新能力。
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '1'
---
