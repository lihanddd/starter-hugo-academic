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
  email: lihanddd@outlook.com
  phone: +86 15101512180
  address:
    city: Beijing
    district: Haidian
    postcode: '100143'
    country: China
    country_code: CN
  office_hours:
    - '09:00 to 24:00'
  appointment_url: 'https://calendly.com'

design:
  columns: '2'
---
