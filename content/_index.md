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
      spacing:
        padding: ['3rem', '0', '2rem', '0']
  - block: collection
    id: activities
    content:
      title: Workshops, Exhibitions & Outreach
      text: Selected activities in knowledge sharing, research engagement, and public outreach.
      count: 4
      sort_by: Date
      sort_ascending: false
      filters:
        folders:
          - activities
      archive:
        enable: true
        link: /activities/
        text: View All Activities
    design:
      view: activity-card
      columns: 2
      show_date: true
      show_read_time: false
      show_read_more: false
      spacing:
        padding: ['2rem', '0', '3rem', '0']
  - block: collection
    id: news
    content:
      title: Latest News
      text: Recent research, publications, awards, and professional updates.
      count: 3
      sort_by: Date
      sort_ascending: false
      filters:
        folders:
          - news
      archive:
        enable: true
        link: /news/
        text: View All News
    design:
      view: date-title-summary
      columns: 1
      show_date: true
      show_read_time: false
      show_read_more: false
      spacing:
        padding: ['3rem', '0', '3rem', '0']
  - block: collection
    id: recent-publications
    content:
      title: Recent Publications
      text: Peer-reviewed journal and conference papers published in 2026.
      filters:
        folders:
          - publications
        tags:
          - Homepage 2026
      count: 0
      sort_by: Weight
      sort_ascending: true
      archive:
        enable: true
        link: /publications/
        text: View All Publications
    design:
      view: publication-compact
      columns: 1
      spacing:
        padding: ['2rem', '0', '3rem', '0']
---
