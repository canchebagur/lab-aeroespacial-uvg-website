---
title: Contacto
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contáctanos
      text: |-
        ¿Tienes preguntas sobre nuestros proyectos o colaboraciones? Escríbenos y con gusto te respondemos.
      email: satelite@uvg.edu.gt
      phone: '+502 2507-1500 Ext. 21284'
      address:
        street: 18 Av. 11-95 Zona 15 Vista Hermosa III
        city: Guatemala
        region: Guatemala
        postcode: '01015'
        country: Guatemala
        country_code: GT
      coordinates:
        latitude: '14.6036'
        longitude: '-90.4890'
      directions: Al llegar a campus, ingresa por la entrada principal y dirígete al edificio de Ingeniería. Recepción del laboratorio en el 2.º nivel.
      office_hours:
        - 'Lunes a viernes, de 7:00 a 18.00 hrs'
      appointment_url: 'https://calendly.com/tulab'
      autolink: true

      # Formulario (Netlify). Déjalo tal cual si despliegas en Netlify.
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          captcha: true   # ponlo en true para reducir spam
    design:
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
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---

