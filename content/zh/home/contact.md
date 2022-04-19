---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: 联系方式
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
  address:
    city: 北京市
    region: 海淀区
    postcode: '100143'
    country: 中国
    country_code: CN
  office_hours:
    - '09:00 to 24:00'

design:
  columns: '2'
---
