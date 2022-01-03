---
title: Kontakt
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |
      Max Treuer

      Philippsanlage 7, 64560 Riedstadt

      maxtreuer@gmail.com

      \+49 (0) 178 7139 392
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Vor und Nachname
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Ihre Email Adresse
        is_required: true
      - input_type: tel
        name: telephone
        label: Telefonnummer
        default_value: Ihre Telefonnummer
        options: []
        is_required: false
        type: form_field
      - input_type: select
        name: subject
        label: Immobilie
        default_value: Bitte auswählen
        options:
          - null
          - Anfrage
          - Sonstiges
        is_required: true
      - input_type: textarea
        name: message
        label: Nachricht
        default_value: Ihre Nachricht
        is_required: true
      - input_type: checkbox
        name: consent
        label: >-
          Ich bin damit einverstanden, dass meine übermittelten Daten zu
          Kontaktaufnahme gespeichert werden dürfen.
        is_required: true
    submit_label: Nachricht versenden
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
