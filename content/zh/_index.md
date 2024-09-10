---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: DELTA
        content: ''
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '390px'
      # is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000
  

  - block: markdown
    content:
      title: |
        欢迎来到 Delta Lab
      # image:
      #   filename: welcome.jpg
      text: |
        <br>
        
        **Delta Lab**隶属于中国河海大学计算机与软件学院，致力于推进计算机视觉领域的发展。我们的研究集中在几个前沿领域：
        - **计算机视觉:** 小样本图像分割，文字检测与识别。
        - **人工智能:** 可解释性人工智能，因果分析。
        - **多媒体计算:** 医学图像分析，图像加密与超分辨率。
        - **智慧水利:** 智能水文过程建模，水文大数据处理与分析。
        
        我们致力于通过理论研究和实际应用推动技术的边界。如果您对计算机视觉及其应用充满热情，我们邀请您加入我们。有关我们研究的更多信息或参与其中，请通过以下方式与我们联系：[wuyirui@hhu.edu.cn](mailto:wuyirui@hhu.edu.cn). 我们期待与您合作。






  - block: collection
    content:
      title: 最新新闻
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
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: 最新发表
      text: ""
      count: 5
      filters:
        folders:
          - publication
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
