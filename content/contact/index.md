---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      email: rbay@ucdavis.edu
      phone: 530 754 1439
      address:
        street: One Shield Ave
        city: Cavis
        region: CA
        postcode: '95616'
        country: United States
        country_code: US
      coordinates:
        latitude: '38.541088'
        longitude: '-121.754595'

#      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
 #     form:
 #       provider: netlify
 #       formspree:
 #         id:
 #       netlify:
          # Enable CAPTCHA challenge to reduce spam?
 #         captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---