---
title: General enquiries
sections:
  - type: hero_section
    template: hero_section
    title: I hope we can keep in touch!
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
    content: "I'm looking for new opportunities! If you are interested in my works or blog posts, please contact me at\_[kangyeon.lee.alicia@gmail.com](mailto:example@example.com)\n"
  - type: form_section
    template: form_section
    content_align: left
    form_position: top
    form_width: sixty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - type: form_field
        template: form_field
        input_type: text
        label: NAME
        default_value: Your name
        is_required: true
        name: NAME
      - type: form_field
        template: form_field
        input_type: email
        name: email
        label: EMAIL
        default_value: Your email address
        is_required: true
      - type: form_field
        template: form_field
        input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - type: form_field
        template: form_field
        input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - type: form_field
        template: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
  title: General Enquiries
  description: This is the general enquiries page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: General Enquiries
      keyName: property
    - name: 'og:description'
      value: This is the general enquiries page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: General Enquiries
    - name: 'twitter:description'
      value: This is the general enquiries page
template: advanced
---
