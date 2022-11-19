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
  email: chinna.devarapu'at'mtu.ie
  phone: 021 433 59 58
  address:
    street: Rossa Avenue
    city: Bishopstown
    region: Cork
    postcode: T12P928
    country: Ireland
    country_code: IE
  
  directions: Find me in Create Building in the Bisopstown campus 

  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/chinnadevarapu'


design:
  columns: '2'
---
