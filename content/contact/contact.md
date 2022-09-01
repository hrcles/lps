---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contato
subtitle:

content:
  # Contact (edit or remove options as required)

  email: teste@exemplo.org
  phone: 888 888 88 88
  address:
    street: Rua Augusto Corrêa, 01
    city: Belém
    region: PA
    postcode: '66075-110'
    country: Brasil
    country_code: BR
  coordinates:
    latitude: '-1.4760012275027468'
    longitude: '-48.45725581683158'
  directions: Instituto de Letras e Comunicação, segundo andar, sala 17
  office_hours:
    - 'Segunda: 9h30 às 11h (Manhã)'
    - 'Terça: 14h30 as 16h (Tarde)'
    - 'Quarta: 9h30 às 11h (Manhã)'
    - 'Sexta: 9h30 às 11h (Manhã)'
  appointment_url:
    - https://calendar.google.com/calendar/u/0/r
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

design:
  columns: '1'
---

Envie seu comentário, sugestão, opiniões, contribuições e afins para nós!
