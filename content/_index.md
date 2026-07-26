---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research lies at the intersection of generative modelling,
        computational imaging, signal processing, and intelligent sensing.
      
        I investigate diffusion models and implicit neural representations for
        image restoration and generative modelling, while also developing
        multispectral-imaging and machine-learning methods for agricultural,
        environmental, and industrial applications.
    design:
      columns: '1'
  - block: collection
    id: news
    content:
      title: Latest News
      text: Recent research, publications, awards, and professional updates.
      filters:
        folders:
          - news
      count: 4
    design:
      view: compact
      columns: 1
      show_date: true
      show_read_time: false
      show_read_more: false
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
