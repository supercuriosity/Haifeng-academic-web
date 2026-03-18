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
      button:
        text: Download CV
        url: uploads/resume.pdf
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
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research focuses on Embodied AI, Robotics, and Computer Vision. I develop knowledge- and reasoning-driven frameworks that enable intelligent agents to perceive human activities, understand behavioral logic, learn from demonstrations, and adaptively interact with complex environments. My goal is to create embodied robots that can generalize across tasks, infer human intentions, and collaborate safely and intelligently in the real world.
    design:
      columns: '1'
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
      columns: 2
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
