---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Activate this widget? true/false
active: false

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
  email: xie.1295@osu.edu
  address:
    street: 1885 Neil Ave
    city: Columbus
    region: OH
    postcode: '43210'
    country: United States
    country_code: US
  office_hours:
    - 'Monday to Friday 2:00 pm to 6pm'
  appointment_url: 'https://calendly.com'


design:
  columns: '2'
---
