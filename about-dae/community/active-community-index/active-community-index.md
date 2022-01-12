---
type: table
title: Active Community Index
nav: ''
menu: false
template: index-list
core: true
status: Draft
publish_on: ''
display_until: ''
layout:
  - size: 5
    blocks:
      - type: table
        size: 10
---

type: table
label: Data
fields:
  - label: Position at DAE
    type: select
    value:
      - Student
      - Staff
      - Tutor
    visible: true
    selected: ''
    toggle:
    - token: student
      field: Study Year
      type: text
    - token: student
      field: Department
      type: select
    - token: tutor
      field: Department
      type: select
    - token: staff
      field: Job Title
      type: text
  - label: Study Year
    type: select
    value:
      - '1'
      - '2'
      - '3'
    visible: true
    selected: 'false'
  - label: Department
    type: select
    value:
      - Food Non Food
      - Public Private
      - Well-Being
      - Motion
      - Leisure
      - Identity
      - Activity
      - Communication
      - Contextual Design
      - Social Design
      - Information Design
      - Critical Inquiry Lab
      - Geo-Design
      - Studio Collaborative Solutions
      - Studio Identity
      - Studio Living Matter
      - Studio Moonshots
      - Studio Turn Around!
      - Studio Urgencies
      - The Invisible Studio
      - The Morning Studio
  - label: Job Title
    type: text
    value: ''
  - label: DAE Alumni
    type: checkbox
    value: false
    toggle:
      - field: Graduation Department
        type: text
      - field: Graduation Year
        type: text
---
