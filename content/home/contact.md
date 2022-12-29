---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: magadanluis@uniovi.es
  phone: 985 182 607
  address:
    street: Edif. Polivalente - Desp. 2.6.02 - Campus de Gijón
    city: Gijón
    region: Asturias
    postcode: '33203'
    country: Spain
    country_code: ES

design:
  columns: '2'
---
