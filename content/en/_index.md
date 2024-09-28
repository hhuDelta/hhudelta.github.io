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
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Talk & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: talk.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Join Delta Lab
        content: ''
        align: right
        background:
          image:
            filename: join.jpg
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
      slide_height: '450px'
      # is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000
  

  - block: markdown
    content:
      title: |
        Delta Lab welcomes you!
      # image:
      #   filename: welcome.jpg
      text: |
        <br>
        
        **Delta Lab**, part of the School of Computer and Software at Hohai University, China, is dedicated to advancing the field of computer vision. Our research focuses on several cutting-edge areas:

        - **Computer Vision:** We specialize in few-shot learning for image segmentation and end-to-end text detection and recognition.
        - **Artificial Intelligence:** Our work includes explainable AI and causal reasoning, aiming to make AI systems more transparent and understandable.
        - **Multimedia Computing:** We explore medical image analysis, image encryption, and super-resolution methods to enhance multimedia data processing.
        - **Intelligent Water Conservancy:** We apply artificial intelligence techniques to process hydrology big data, supporting advancements in water resource management.

        At Delta Lab, we are committed to pushing the boundaries of technology through both theoretical research and practical applications. If you are passionate about computer vision and its applications, we invite you to join us. For more information about our research or to get involved, please contact us at [wuyirui@hhu.edu.cn](mailto:wuyirui@hhu.edu.cn). We look forward to collaborating with you.






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
      title: Latest Publications
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
