---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: neonowl.systems agency - micro-enterprise design services
      text: transparent, accessible design and development of engineered systems for individuals and small organizations
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-neonowl.jpg
          filters:
            brightness: 0.3
  - block: cta-image-paragraph
    id: program
    content:
      items:
        - title: In Development
          text: Free, Open Source systems for Creative Enterprises
          feature_icon: check
          features:
            - creative writing system
            - niche marketing system
            - web publishing system
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Coming Soon
            url:
      design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
