---
title: UVG Aerospace Laboratory
date: 2024-12-10
type: landing

sections:
  - block: hero
    design:
      flip: false
    content:
      title: |
        <strong>
        UVG
        Aerospace Laboratory
        </strong>
      image:
        filename: logo-lab.jpg
      text: |
        <br>
        
        <div style="text-align: justify;">
        <strong>Pioneers of Guatemalan space development!</strong>
        <br><br> 
        
        We are the research team behind <strong>QUETZAL-1</strong>, the first Guatemalan satellite successfully launched into space in 2020, and we are currently working on the development of <strong>QUETZAL-2</strong>, taking Central American aerospace technology to new heights 🚀
        </div>
        
  - block: collection
    id: news
    content:
      title: |
        <strong>
        Recent News
        </strong>
      subtitle: |
        <div style="text-align: justify;">
        Updates on events, progress, and laboratory activities.
        </div>
      text: ''
      count: 2            
      filters:
        folders:
          - post          
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      order: desc
    design:
      view: compact       
      columns: '2'

  - block: collection
    id: publications
    content:
      title: 
        <strong>
        Recent Publications
        </strong>
      subtitle: |

        <div style="text-align: justify;">
        Recent publications showcasing the progress and results of our research and technological development projects.
        </div>

      text: ''
      count: 3
      filters:
        folders:
          - publication
        publication_type: ''
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      order: desc
    design:
      view: citation
      columns: '2'
---