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
  email: thindle2016@fau.edu
  phone: 561 569 6124
  address:
    #street: 
    city: Boca Raton
    region: Florida
    #postcode: '33431'
    country: United States
    country_code: US
  coordinates:
    latitude: '26.3735'
    longitude: '-80.0964'
  #directions: Building 26 Room 92
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: twitter
  #    icon_pack: fab
  #    name: DM Me
  #    link: 'https://twitter.com/Twitter'
  #  - icon: video
  #    icon_pack: fas
  #    name: Zoom Me
  #    link: 'https://zoom.com'

design:
  columns: '2'
---
