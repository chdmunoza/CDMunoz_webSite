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
  email: daniel.munoz@npl.co.uk
  phone: +44 111 222 111
  address:
    street: Hampton Road
    city: Teddington
    region: CA
    postcode: 'TW11 0LW'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Building 5 Office F5-A4 on Floor 1
  office_hours:
    - 'Monday 08:00 to 12:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
