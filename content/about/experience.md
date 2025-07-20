---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Researcher
    company: Graz University of Technology
    company_url: ''
#    company_logo: org-gc
    location: California
    date_start: '2024-10-01'
    date_end: '2025-03-01'
    description: |2-
        Responsibilities include:
        
        * Designed an auto-labeling framework that ensembles UPerNet, OCRNet, and DeepLabV3+ using logit fusion and SDF-weighted integration for consistent semantic segmentation predictions.
        * Refined ambiguous regions and boundries using zero-shot instance segmentation with the foundation model SAM, enabling label-agnostic fusion of semantic and instance outputs.
        * Achieved a 5.8% mIoU improvement over the best individual model while reducing annotation time to ∼ 3 seconds per image, significantly minimizing manual effort.

#  - title: Professor of Semiconductor Physics
#    company: University X
#    company_url: ''
#    company_logo: org-x
#    location: California
#    date_start: '2016-01-01'
#    date_end: '2020-12-31'
#    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '1'
---
