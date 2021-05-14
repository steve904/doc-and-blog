---
title: Home
sections:
  - section_id: hero
    type: section_hero
    title: Doc and Blog
    image: images/5.jpg
    content: >-
      Welcome to Doc and Blog. Stephen Causey here and wherever you are...enjoy!
    actions:
      - label: Get Started
        url: /docs
        style: primary
      - label: Let's Go!
        url: '#'
        style: link
        icon_class: dev
        new_window: false
        no_follow: false
        type: action
  - section_id: features
    type: section_grid
    col_number: two
    grid_items:
      - title: Documentation
        content: >
          Documentation or "Docs" are here. **You probably will like the Blog
          more than the Docs.** The Docs can also be used to archive blog post.
        actions:
          - label: Docs
            url: /docs
            style: link
      - title: Blog
        content: >
          This is where all the blog posts live. Just click on the button & you
          will be there.
        actions:
          - label: Blog
            url: /blog
            style: link
  - section_id: text-img
    type: section_content
    image: images/jamstack.svg
    image_position: left
    title: A Section With An Image
    content: >
      Yes, a section with an image. You can use this in this site. Check how it
      works in the markdown pages.
    actions:
      - label: View Demo
        url: /docs/getting-started
        style: primary
      - label: Docs
        url: /docs/getting-started
        style: secondary
        actions:
          - label: View Demo
            url: /blog/cat
            style: primary
          - label: Docs
            url: /blog/cat
            style: secondary
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
