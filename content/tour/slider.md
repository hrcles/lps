---
widget: slider
weight: 1
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
    - title: 👋 Bem-vindo ao Laboratótio!
      content: Veja no que estamos trabalhando...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: sala.jpg
    - title: Aprenda conosco! ☕️
      content: 'Participe de nossas oficinas e cursos!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: turma.jpg
    - title: Turmas de português para surdos abertas!
      content: 'Veja como participar!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: curso.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Faça parte
        url: ../contact/
---
