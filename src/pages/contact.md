---
form_action: /contact-success
form_fields:
  - default_value: Your name
    input_type: text
    is_required: true
    label: Name
    name: name
    type: form_field
  - default_value: Your email address
    input_type: email
    is_required: true
    label: Email
    name: email
    type: form_field
  - default_value: Please select
    input_type: select
    label: Subject
    name: subject
    options:
      - Error on the site
      - Sponsorship
      - Other
    type: form_field
  - default_value: Your message
    input_type: textarea
    label: Message
    name: message
    type: form_field
  - input_type: checkbox
    label: >-
      I understand that this form is storing my submitted information so I can
      be contacted.
    name: consent
    type: form_field
form_id: contactForm
img_alt: Post in the door mailbox
img_path: >-
  https://cdn.sanity.io/images/ugp17u07/production/f79d5c8c4b430a858067e2d20677da42b4c19729-1200x823.jpg
seo:
  description: This is the contact page
  extra:
    - keyName: property
      name: 'og:type'
      value: website
    - keyName: property
      name: 'og:title'
      value: Get in Touch
    - keyName: property
      name: 'og:description'
      value: This is the contact page
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Get in Touch
    - name: 'twitter:description'
      value: This is the contact page
  title: Get in Touch
  type: stackbit_page_meta
stackbit_url_path: /contact
submit_label: Send Message
template: contact
title: Get in Touch
---

Fill the form below to get in touch with me.
