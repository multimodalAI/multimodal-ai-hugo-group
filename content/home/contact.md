---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Contact Us
subtitle:

content:
  # Contact (edit or remove options as required)
  email: 
  address:
    street: The Edge, The Endcliffe Village, 34 Endcliffe Cres
    city: Sheffield
    region:
    postcode: 'S10 3ED'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '53.372795238367225'
    longitude: '-1.5074086064770071'
  #directions:
  #appointment_url: 'https://calendly.com'
  contact_links:
    - icon: pen
      icon_pack: fas
      name: Register
      link: 'https://multimodalai.github.io/'

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
  columns: '2'
---

