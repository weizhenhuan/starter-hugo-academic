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
  email: zhenhuan2002@163.com
#   phone: 888 888 88 88
  address:
    street: 长安区兴隆街道
    city: 西安市
    region: 陕西省
    postcode: '710126'
    country: China
    country_code: CN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: 西安电子科技大学南校区
  office_hours:
    - 'All Day'
    # - 'Wednesday 09:00 to 10:00'
#   appointment_url: 'https://calendly.com'
#   contact_links:
#     - icon: twitter
#       icon_pack: fab
#       name: DM Me
#       link: 'https://twitter.com/Twitter'
#     - icon: video
#       icon_pack: fas
#       name: Zoom Me
#       link: 'https://zoom.com'

design:
  columns: '2'
---
