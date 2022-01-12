---
type: table
title: Simone Niquille
nav:
  toggle: true
  value: ''
menu:
  toggle: false
template: Profile
visibility: Dae
core: false
status: Draft
layout:
  - size: 3
    blocks:
      - type: image
        size: 10
  - size: 3
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
---

type: image
url: a3M9dRK9_700w_0.jpg
caption: ''

---

type: table
fields:
  - label: Firstname
    type: text
    value: Simone
    size: 5
    visible: true
  - label: Lastname
    type: text
    value: Niquille
    size: 5
    visible: true
  - label: Preferred Pronouns
    type: text
    value: she/her
    size: 10
    visible: true
  - label: Languages
    type: text
    value: 'German, English, Dutch'
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
    value: '@technoflesh'
    size: 10
    visible: true
  - label: Twitter
    type: text
    value: '@technoflesh'
    size: 10
    visible: true
  - label: Position at DAE
    type: select
    selected: ''
    size: 10
    visible: true
  - label: Department
    type: select
    selected: ''
    visible: true
    size: 10
  - label: Study Year
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
    visible: true
    fields:
      label: DAE Alumni
      type: checkbox
      value: false
      toggle:
        - field: Graduation Department
          type: text
        - field: Graduation Year
          type: text
  - label: Department
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
