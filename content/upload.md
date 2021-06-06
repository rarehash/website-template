---
title: Upload hash
sections:
  - type: form_section
    content: >-
      ## Añade un nuevo hash


      Llena correctamente el siguiente formulario para publicar nuevos documentos o archivos.
    content_align: center
    form_position: center
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: email
        name: email
        label: Correo electronico
        default_value: radioactivedays@gmail.com
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
seo:
  title: Contacto
  description: Rarehash, contact.
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contacto
      keyName: property
    - name: 'og:description'
      value: Rarehash, contact.
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contacto
    - name: 'twitter:description'
      value: Rarehash, contact.
layout: advanced
---
