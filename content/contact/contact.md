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
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Instituto de Letras e Comunicação, segundo andar, sala 17
  office_hours:
    - 'Segunda à Sexta'
    - 'Manhã: 8h às 12h'
    - 'Tarde: 14h às 17h'
  appointment_url: 'https://calendly.com'
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
