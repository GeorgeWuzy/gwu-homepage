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
  email: haooyang-li@outlook.com
  phone: (+86) 191-217-23032
  address:
    street: 4800 Cao’an Highway
    city: Shanghai
    region: Shanghai
    country: China
    country_code: CN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  office_hours:
    - 'Workday 08:00 to 17:30'

design:
  columns: '2'
---
