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
  email: 2030528@tongji.edu.cn
  phone: 86-021-13371852150
  address:
    street: No.1239 Siping Road
    city: Shanghai
    region: Yangpu District
    postcode: '200092'
    country: China
    country_code: CHN
  coordinates:
    latitude: '37.427531.28330102310079'
    longitude: '-122.1697121.50085545468757'
  directions: 
  office_hours:
    - 'Everyday 8:00 to 21:00'
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
