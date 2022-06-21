---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: eike.langbehn@haw-hamburg.de
  phone: +49 40 42875 7621
  address:
    street: Finkenau 35
    city: Hamburg
    region: Hamburg
    postcode: '22081'
    country: Germany
    country_code: DE
  coordinates:
    latitude: '53.56855'
    longitude: '10.03375'
  directions: Enter main building and take the floor to the right
  office_hours:
    - 'Tuesday 11:00 to 13:00'
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
