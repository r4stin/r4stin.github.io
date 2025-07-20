---
# An instance of the Contact widget.
# Documentation: https://docs.hugoblox.com/getting-started/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Get in touch
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
#  form:
#    provider: netlify
#    formspree:
#      id:
#    netlify:
#      # Enable CAPTCHA challenge to reduce spam?
#      captcha: false
  form:
    provider: netlify
    netlify:
      captcha: false
    fields:
      - name: name
        label: Name
        type: text
      - name: email
        label: Email
        type: email
      - name: message
        label: Message
        type: textarea
    button:
      text: Send Message


design:
  columns: '1'
---
