---
type: table
title: Esther de Bruijn
nav:
  toggle: true
  value: ''
menu:
  toggle: false
  value: ''
template: Profile
visibility: World
core: true
status: Published
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
---

type: image
url: alyster.jpg
caption: ''

---

type: table
fields:
  - label: Firstname
    type: text
    value: Esther
    size: 5
    visible: true
  - label: Lastname
    type: text
    value: de Bruijn
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

At DAE Esther fulfills the post of XR Officer: a title that is still rather unknown - she does practical research in all kinds of interactive fields, a.o. in VR, AR, and comparable settings – all this to support the Research department practically and conceptually.

Esther has an enormous interest for new technologies, especially in the art world, and continuously updates herself or taking on new projects that are on the limits of her skillset - just so she can expand them. She believes that technologies should be a natural augmentation of our bodies and minds. After graduating at the KABK in the Hague she has been expanding her knowledge by starting up Studio Vodka, where she creates 3D art, VR experiences, and light installations.

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
    selected: Staff
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
