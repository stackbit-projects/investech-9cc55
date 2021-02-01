---
title: Contacto
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - input_type: text
    name: name
    label: Nombre
    default_value: Tu nombre
    is_required: true
  - input_type: email
    name: email
    label: Email
    default_value: Tu email
    is_required: true
  - input_type: text
    name: subject
    label: Asunto
    default_value: Tu asunto
    options: []
    is_required: true
  - input_type: textarea
    name: Mensaje
    label: Message
    default_value: Tu mensaje
  - input_type: checkbox
    name: consent
    label: Entiendo que enviando este formulario se me puede contactar
    is_required: true
submit_label: Enviar
template: contact
---
Puedes contactarme utilizando el formulario inferior
