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
      captcha: true

  # Contact details (edit or remove options as required)
  email: daniel.munoz@npl.co.uk
  phone: +44 20 8943 6369
  address:
    street: Hampton Road
    city: Teddington
    region: Middlesex
    postcode: 'TW11 0LW'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '51.4262404'
    longitude: '-0.3436875'
  directions: Building 5 Office F5-A4 on Floor 1
  office_hours:
    - 'Monday 08:00 to 12:00'
    - 'Wednesday 08:00 to 12:00'

design:
  columns: '2'
---
