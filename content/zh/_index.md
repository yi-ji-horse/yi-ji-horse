---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        随机矩阵
        光学课题组
      image:
        filename: research_topic.jpg
      text: |
        <br>
        
        随机矩阵光学将随机矩阵工具箱引入到光波粒二象性的表示中。从 2019 年开始，我们团队专注于利用随机矩阵表示法对光场进行表示、分解、检测和操控。随机矩阵表示为光场中的不同成分提供了一种统计选通策略。例如，在宽场反射成像中的单次散射和多次散射成分；在光谱域光学相干断层扫描中的弹道散射和多次散射成分。选通后的多次散射成分有助于活体组织成像中吸收信息的计算。
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
