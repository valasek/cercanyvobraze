---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Napište nám
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
  email: cercany.vobraze@gmail.com
  # phone: 888 888 88 88
  # address:
  #   street: 450 Serra Mall
  #   city: Stanford
  #   region: CA
  #   postcode: '94305'
  #   country: United States
  #   country_code: US
  # coordinates:
  #   latitude: '37.4275'
  #   longitude: '-122.1697'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: facebook
      icon_pack: fab
      name: 'Přidej se do FB skupiny'
      link: 'https://www.facebook.com/groups/367013960544384/'
    - icon: youtube
      icon_pack: fab
      name: 'Sleduj nás na YouTube'
      link: 'https://www.youtube.com/channel/UCf6ROd0g3jU5U4jpO857--g/videos'
  
design:
  columns: '2'
  background:
    image: cercany.jpg  # Name of image in `static/img/`.
    image_darken: 0.6
    image_position: center
    image_parallax: true
    text_color_light: true

---
