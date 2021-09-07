---
title: Contact
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: >
      Merci pour votre intérêt.

      Si vous voulez plus d’informations sur les ressources proposées ou sur les
      cours particuliers, n’hésitez pas à me contacter par e-mail
      contact@camille-toussaint.fr


      ***
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nom
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Votre message
    submit_label: Envoyer
  - section_id: lorem-ipsum
    title: Contact
    subtitle: lorem-ipsum
    image_alt: lorem-ipsum
    content: >-
      ## Lorem ipsum


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua.


      - Lorem ipsum

      - dolor sit amet
    type: content_section
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
