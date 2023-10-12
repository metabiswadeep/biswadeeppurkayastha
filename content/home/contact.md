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
  email: bpdps95@hotmail.com
  phone: 9831268042
  address:
    street: B14 306, Indian Institute of Technology Mandi
    city: Himachal Pradesh
    postcode: '175005'
    country: India
  coordinates:
    
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Connect
      link: 'https://linkedin.com/in/bp05'
    - icon: fa-envelope
      icon_pack: fa
      name: Email
      link: 'mailto:bpdps95@hotmail.com'

design:
  columns: '2'
---
