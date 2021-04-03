---
layout: home
title: Home
white_header: true

sections:


  - type: hero_section
    section_id: hero_section
    background_image: images/header.jpg
    background_image_opacity: 100
    content: >-
      # La capsule
      
      ## cabinet de curiosité
      
    actions:
      - title: Entrée
        url: /store
        arrow: false
        style: primary


  - type: featured_products_section
    section_id: produit_a_la_une
    title: Meilleures Ventes
    icon: true
    light_title: true

    featured_products:
      - content/products/cafe.md
      - content/products/grandcafe.md
      - content/products/biere.md
      - content/products/petard.md

  - type: featured_categories_section
    section_id: featured_categories_section

    featured_categories:
      - content/category/bigplants.md
      - content/category/cactuses.md

  - type: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - author:
          name: John Dope
          location: 'Colorado, USA'
        text: >-
          I didn't know the Snipcart guys were into herbs as well! How beautiful
          is that Planty theme. I'm going to launch a killer JAMstack e-commerce
          store using this for sure.
      - author:
          name: Major Payne
          location: 'VA, USA'
        text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.


  - type: promotion_section
    section_id: promotion_section
    title: Demander vous l'aurez
    subtitle: à partir de
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      title: Découverte
      url: /store
      style: secondary
      arrow: true
---
