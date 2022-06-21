---
draft: false
showcontact: true
index: true
showcart: false
showsearch: false
custom:
  - type: data
    key: contact_agree
    value: "false"
title: Contact Us
description: If you are in need to get in touch with us, we are happy to reply.
  Create a New Message below.
featured_image: /images/support-banner.jpeg
cover_photo:
  color: white
  shade: ""
  font: aguafina
form:
  action: https://docs.google.com/forms/u/4/d/e/1FAIpQLScwOVTvhzsPnaT-NweTHKhMT15Ja3m06uL7d7bWZXPF5WGQsw/formResponse?embedded=true
  method: POST
  button:
    text: Submit
  recaptcha:
    enable: true
    siteKey: 6Lf5bYYgAAAAANQkEOJZGw7In3rsYHu7hfrOilhD
  agreement:
    enable: true
    text: I have read and agreed to
    links:
      - name: privacy policy
        link: "#privacy"
      - name: cookie policy
        link: "#cookie"
  fields:
    - name: entry.2131373238
      label: Name
      type: text
      value: name
      validation:
        required: true
        pattern: ^[a-zA-Z]+(([',. -][a-zA-Z ])?[a-zA-Z]*)*$
        title: Special Characters and Number Not Allowed.
        minLength: ""
      tag: input
      placeholder: Juan Dela Cruz
    - name: emailAddress
      label: Email
      type: email
      value: email
      validation:
        required: true
      tag: input
      placeholder: juandelacruz@gmail.com
    - name: entry.1118811649
      label: Contact No.
      type: text
      value: mobile
      validation:
        required: true
        pattern: ((^(\+)(\d){12}$)|(^\d{11}$))
        title: Must Start With +639XXXXXXXXXX or 09XXXXXXXXXX
      tag: input
      placeholder: "+63915123456789"
    - name: entry.1198593499
      label: Message
      type: text
      value: message
      validation:
        required: true
      tag: textarea
      placeholder: Type Your Questions Here...
slug: support
sections:
  - template: contact/form
  - template: contact/mobiles
  - template: contact/locations
pick_up_locations:
  title: Pick Up Location
  locations: []
mobiles:
  title: Call / Text Us
  mobiles: []
---
