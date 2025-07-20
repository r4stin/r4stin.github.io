---
# An instance of the About widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: publications

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Publications test

content:
  page_type: publication
  filter_default: 0
  filter_button:
    - name: All
      tag: "*"
    - name: Conferences & Journals
      tag: Conference
    - name: Challenges
      tag: Challenge
    - name: Theses
      tag: Thesis

design:
  view: masonry
  columns: "2"
---
