---
title: Contact
sections:
  - type: hero_section
    title: Contáctame
    subtitle: >-
      Rellena el siguiente formulario y a la brevedad me pongo en contacto
      contigo.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ## Letra chica


      Si en algún momento desea cancelar nuestro proyecto, debe proporcionar un
      aviso por escrito de 30 días, después de lo cual le transferiré todos sus
      activos para que pueda usarlos en cualquier momento.
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Correo electrónico
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mi información enviada
          para que pueda ser contactado.
        is_required: true
    submit_label: Enviar mensaje
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
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
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
