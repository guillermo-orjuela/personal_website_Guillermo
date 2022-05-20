---
# Use the Slider widget as this page section
widget: slider  
# Position of this section on the page
weight: 40  
# Publish this section?
active: false
# This file represents a page section.
headless: false

design:
# Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
# Automatically transition through slides?
  loop: true
# Duration of transition between slides (in ms)
  interval: 3000

content:
  slides:
    - title:  Bibliometriar
      content: "A website for bibliometric analysis using R"
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        # media: coders.jpg
    - title: Current teaching courses
      content: "Academic writing for undergraduate students"
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        # media: contact.jpg
      link:
        icon: coffee
        icon_pack: fas
        text: Blog of the course
        url: ../courses/

---

