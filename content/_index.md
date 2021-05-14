---
title: Home
sections:
  - section_id: hero
    type: section_hero
    title: Doc and Blog
    image: images/5.jpg
    content: |
      I'm Stephen Causey. Welcome to Doc and
      Blog
    actions:
      - label: Docs
        url: /docs
        style: secondary
      - label: Blog
        url: /blog
        style: secondary
        icon_class: dev
        new_window: false
        no_follow: false
        type: action
  - section_id: features
    type: section_grid
    col_number: two
    grid_items:
      - title: Documentation
        content: |
          *Photo by Thom Milkovik - Unsplash*
        actions:
          - label: Docs
            url: /docs
            style: link
        image: images/thom-milkovic-800opx.jpg
        title_url: /docs
      - title: Blog
        content: |
          *Photo by Rhondak - Unsplash*
        actions:
          - label: Blog
            url: /blog
            style: link
        image: images/rhondak-native-800px.jpg
        title_url: /blog
  - section_id: text-img
    type: section_content
    image: images/jamstack.svg
    image_position: left
    title: A Section With An Image
    content: >
      Yes, a section with an image. You can use this in this site. Check how it
      works in the markdown pages.
    actions:
      - label: Docs
        url: /docs/
        style: primary
      - label: Blog
        url: /blog
        style: primary
  - section_id: text-no-img
    type: section_content
    title: A Section Without Image
    content: >-
      Nam pulvinar ante eu ultricies volutpat. Sed nulla nibh, dapibus sit amet
      cursus quis, fringilla nec sapien. Vestibulum imperdiet nunc bibendum
      consectetur lobortis.
    actions:
      - label: Get Started
        url: /docs/getting-started/installation
        style: primary
  - section_id: features-two-col
    type: section_grid
    title: Sample Layouts
    subtitle: Some very nice layouts
    col_number: two
    grid_items:
      - title: Overview
        content: |
          Go to the overview page ------->
        actions:
          - label: Learn More
            url: /overview
            style: link
      - title: Showcase
        content: |
          Some very nice theme that you can use through Stackbit or Jamstack.
        actions:
          - label: Learn More
            url: /showcase
            style: link
  - section_id: cta
    type: section_cta
    title: Doc and Blog
    subtitle: Where it happens in one place...Doc and Blog
    actions:
      - label: Get Started
        url: /docs/getting-started/installation
        style: primary
seo:
  title: Stackbit Libris Theme
  description: The preview of the Libris theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit Libris Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Libris theme
      keyName: property
    - name: 'og:image'
      value: images/4.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit Libris Theme
    - name: 'twitter:description'
      value: The preview of the Libris theme
    - name: 'twitter:image'
      value: images/4.jpg
      relativeUrl: true
layout: advanced
---
