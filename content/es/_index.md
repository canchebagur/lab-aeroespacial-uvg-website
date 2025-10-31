---
title: Laboratorio Aeroespacial UVG
date: 2024-12-10
type: landing

sections:
  - block: hero
    design:
      flip: false
    content:
      title: |
        <strong>
        Laboratorio Aeroespacial
        UVG
        </strong>
      image:
        filename: logo-lab.jpg
      text: |
        <br>
        
        <div style="text-align: justify;">
        <strong>¡Pioneros del desarrollo espacial guatemalteco!</strong>
        <br><br> 
        
        Somos el equipo de investigación responsable del <strong>QUETZAL-1</strong>, el primer satélite guatemalteco lanzado exitosamente al espacio en 2020, y actualmente trabajamos en el desarrollo del <strong>QUETZAL-2</strong>, llevando la tecnología aeroespacial centroamericana a nuevas alturas 🚀
        </div>
        
  - block: collection
    id: news
    content:
      title: |
        <strong>
        Noticias Recientes
        </strong>
      subtitle: |
        <div style="text-align: justify;">
        Actualizaciones sobre eventos, avances y actividades del laboratorio.
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
        Publicaciones Recientes
        </strong>
      subtitle: |

        <div style="text-align: justify;">
        Publicaciones recientes que muestran los avances y resultados de nuestros proyectos de investigación y desarrollo tecnológico.
        </div>

      text: ''
      count: 5
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