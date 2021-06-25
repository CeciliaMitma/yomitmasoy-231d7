---
title: Contacto
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      ¡Hola! Muchas gracias por tu interés en contactarme. Por favor llena este
      formulario o envíame un correo a esta dirección cecilia.mitma@gmail.com
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Coloca tu nombre
        is_required: true
      - input_type: email
        name: 'Direccion '
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Tipo
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Enviar
seo:
  title: Contacto
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contacto
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contacto
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
