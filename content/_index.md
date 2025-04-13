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
      title: neonowl.website
      text: "Creativity is combining things. -- Steve Jobs"
      primary_action:
        text: Hugo Blox Docs
        url: https://docs.hugoblox.com/
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
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: features
    id: about
    content:
      title: About
      text: A website built with blocks 🧱
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
