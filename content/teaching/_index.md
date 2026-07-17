---
title: Teaching
summary: My courses
type: landing

build:
  list: never
  render: never

cascade:
  - _target:
      kind: page
    build:
      list: never
      publishResources: false
      render: never
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: 2
---
