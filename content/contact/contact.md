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

  email: joe.bathelt@rhul.ac.uk
  address:
    street: Royal Holloway, University of London
    city: Egham
    region: Surrey
    postcode: 'TW20 0EX'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '51.42623136610804'
    longitude: '-0.5619561955640539'
  directions: Wolfson Building, 1st Floor
  office_hours:
    - 'Tuesday 13:00 to 14:00'
    - 'Thursday 12:00 to 13:00'
  appointment_url: 'https://fantastical.app/joebathelt/meet-with-me'
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
