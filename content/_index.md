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
      title: neonowl Business Systems (noBS)
      text: creative systems thinking as a service
      primary_action:
        text: View Program
        url: /#program
        icon: rocket-launch
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
        - title: Host a Private Screening
          text: Book the Eastside Cinema for your Private Screening or Event
          feature_icon: check
          features:
            - Our cinema is YOUR CINEMA!
            - We have an option for everyone!
            - Nonprofit Organizations--$100 discount
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Book Now!
            url: /eastside-cinema-private-rental-request
      design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
