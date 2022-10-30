---
widget: slider
weight: 10
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: 500px
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Chou Lab at University of Toronto
      content: Programmable molecular and nanotechnologies for  <br> next-generation analytics and precision medicine
      align: left
      background:
        position: center
        color:
        brightness: 0.9
        media: factory-1400x500.png

      link: 
        icon : "search"
        icon_pack : "fas"
        text: "Our research"
        url: "/research"

    - title: Latest News
      content: Find out about the latest happenings in the lab
      align: left
      background:
        position: top
        color: '#666'
        brightness: 0.6
        media: laboratory-panorama.jpg

      link: 
        icon : "search"
        icon_pack : "fas"
        text: "Learn More"
        url: "/post"

    - title: Multi-disciplinary team
      content: We are an interdisciplinary research group working at the interface of engineering, biology, materials chemistry, and computer science
      align: left
      background:
        position: top
        color: '#666'
        brightness: 0.6
        media: lab-dinner.jpg

      link: 
        icon : "graduation-cap"
        icon_pack : "fas"
        text: "Meet the team"
        url: "/people"

    - title: Join Us
      content: If you are self-motivated, innovative, and highly passionate about engineering biology to improve human health, we want to hear from you
      align: left
      background:
        position: top
        color: '#666'
        brightness: 0.6
        media: UofTEng-1400x500.png

      link: 
        icon : "map-marked"
        icon_pack : "fas"
        text: "Get in touch"
        url: "/contact"

---