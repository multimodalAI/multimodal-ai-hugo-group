---
widget: slider
weight: 1
active: true
headless: false

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
    - title: First Workshop on Multimodal AI
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.6
        media: slide.jpg
      content: >
        <font size="4.9" style="color: white !important;">With unimodal AI maturing, what new doors will multimodal AI open for us? <br> 27th June 2023, Sheffield S10 3ED</font>
        <div style="text-align: center;">
          <a href="https://multimodalai.github.io/" class="btn" style="margin: 5px; background-color: white !important; color: purple !important;"><i class="fas fa-pen"></i> Register Now</a>
          <a href="https://twitter.com/MultimodalAI_UK" class="btn" style="margin: 5px; background-color: white !important; color: purple !important;"><i class="fab fa-twitter"></i> Follow Us</a>
        </div>
    - title: Lunch & Learn ☕️
      content: 'Share your knowledge in our first MultimodalAI Workshop and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media:
    - title: Under Construction
      content: 'This website is under construction.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media:
      link:
        icon: fa-github
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
