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
        text: View
        url: /#services
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
  - block: markdown
    id: services
    content:
      title: Services
      subtitle: Currently being offered
      text: >-
        Private Screening Booking System <br /><br />
        <a href="/host-a-private-screening">Eastside Cinema; 1156 Hargrave Street</a>
    design:
      columns: 1
---
