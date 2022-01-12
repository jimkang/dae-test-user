---
type: table
title: Me2
template: Profile
visibility: Dae
layout:
  - size: 3
    blocks:
      - type: image
        size: 10
  - size: 5
    blocks:
      - type: table
        size: 9
      - type: text
        size: 10
        font: f-15-18
  - size: 2
    blocks:
      - type: table
        size: 10
core: false
nav: false
menu: false
status: Published
---

type: image
url: ''
caption: ''

---

type: table
fields:
  - label: Firstname
    type: text
    value: Me2
    size: 5
    visible: true
  - label: Lastname
    type: text
    value: Again
    size: 5
    visible: true
  - label: Preferred Pronouns
    type: text
    value: ''
    size: 10
    visible: true
  - label: Languages
    type: text
    value: ''
    size: 10
    visible: true

---



---

type: table
fields:
  - label: Email
    type: text
    value: ''
    size: 10
    visible: true
  - label: Instagram
    type: text
    value: ''
    size: 10
    visible: true
  - label: Twitter
    type: text
    value: ''
    size: 10
    visible: true
  - label: Position at DAE
    type: select
    selected: ''
    visible: true
    size: 10
  - label: Study Year
    type: select
    selected: ''
    visible: false
    size: 10
  - label: Department
    type: select
    selected: ''
    visible: false
    size: 10
  - label: Job Title
    type: text
    value: ''
    visible: false
    size: 10
  - label: DAE Alumni
    type: checkbox
    value: false
    size: 10
    fields:
      label: DAE Alumni
      type: checkbox
      value: false
      toggle:
        - field: Graduation Department
          type: text
        - field: Graduation Year
          type: text
    visible: true
  - label: Graduation Department
    type: text
    value: ''
    visible: false
    size: 10
  - label: Graduation Year
    type: text
    value: ''
    visible: false
    size: 10

---
