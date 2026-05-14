---
# Leave the homepage title empty to use the site title
title: ""
date: 2026-03-02
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button removed to avoid publishing CV
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: ''
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: markdown
  #   content:
  #     title: 'Updates'
  #     subtitle: ''
  #     text: |- 
  #   design:
  #     columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 1
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: resume-experience
    content:
      title: Experience
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: false
  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: Mind and hand. Thought and tool. This is where my robots begin.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
