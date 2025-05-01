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
      title: neonowl.systems
      text: micro-enterprise design services
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
        - title: Custom System Lifecycle
          text: Jeremy C. Van Doren, Systems Engineer for Hire
          feature_icon: check
          features:
            - design
            - development
            - deployment
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Book a call
            url:
      design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
