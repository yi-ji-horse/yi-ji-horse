---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
#type: landing
type: home_index








heroBlock:
  block: hero
  content:
    title: Random Matrix Optics Research Group
#    image:
#      filename: research_topic.jpg
    text: |
      Random matrix optics introduces the random matrix toolbox to the representation of light wave-particle duality. Starting in 2019, our group focused on light field representation, decomposition, detection, and manipulation using the random matrix representation. Random matrix representation provides a statistical gating strategy for different components in the light field. For example, the single and multiple scattering component in wide-field reflective imaging; the ballistic and multiple scattering component in spectral-domain OCT. The gated multiple scattering component facilitates the calculation of absorption information for in-vivo tissue imaging.
  
heroSlideBlock:
  block: slider
  content:
    slides:
    - title: 
      content: 
      align: center
      background:
        image:
          filename: group_slides/research_topic.jpg
          filters:
            brightness: 1
        position: right
        color: '#666'  
    - title: 
      content: 
      align: left
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 1
        position: right
        color: '#666'  
  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '320px'
    is_fullscreen: false
    # Automatically transition through slides?
    loop: false
    # Duration of transition between slides (in ms)
    interval: 2000


newsBlock:
  block: collection
  content:
    title: Latest News
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


publicationsBlock:
  block: collection
  content:
    title: Latest Publications
    count: 5
    filters:
      folders:
        - publication
#      publication_type: 'article-journal'
      publication_type: 
  design:
    view: card
    columns: '1'      

teamsBlock:
  block: markdown
  content:
    title:
    subtitle:  
    text: |
      {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  design:
    columns: '1'





sections:
  - block: hero
    content:
      title: |
        Random Matrix Optics
        Research Group
      image:
        filename: research_topic.jpg
      text: |
        <br>
        
        Random matrix optics introduces the random matrix toolbox to the representation of light wave-particle duality. Starting in 2019, our group focused on light field representation, decomposition, detection, and manipulation using the random matrix representation. Random matrix representation provides a statistical gating strategy for different components in the light field. For example, the single and multiple scattering component in wide-field reflective imaging; the ballistic and multiple scattering component in spectral-domain OCT. The gated multiple scattering component facilitates the calculation of absorption information for in-vivo tissue imaging.
  
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
  
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen

  - block: collection
    content:
#      title: Latest Preprints
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
#        publication_type: 'article'
        publication_type: 'article-journal'
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
