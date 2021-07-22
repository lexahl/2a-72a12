---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contacto
    content: >
      ¡Queremos ayudarte! Proporcionanos tus datos y nos contactaremos contigo
      lo más pronto posible.
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: Nombre
        label: Asunto
        default_value: Seleccione una opción
        options:
          - Estoy interesado en una máquina expededora
      - input_type: textarea
        name: message
        label: Mensaje
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
