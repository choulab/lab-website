---
widget: slider
weight: 50
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Meet the team
      content:
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: team.jpg

      link: 
        icon : "search"
        icon_pack : "fas"
        text: "learn more"
        url: "/people"
---
