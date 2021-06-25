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
        name: Email
        label: Email
        default_value: Dirección de correo electrónco
        is_required: true
      - input_type: select
        name: subject
        label: Tipo
        default_value: Selecciona uno
        options:
          - Error en la web
          - Sugerencia o comentario
          - Otros
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Escribe aquí tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario almacena mi información enviada para que
          puedan ser contactados.
    submit_label: Enviar
seo:
  title: Contacto
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contacto
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contacto
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
