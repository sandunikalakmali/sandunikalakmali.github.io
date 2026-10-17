---
title: Publications
summary: Peer-reviewed publications and research manuscripts by Sandunika Ranasinghe.
cms_exclude: true
type: landing

sections:
  - block: collection
    content:
      title: Peer-Reviewed Publications
      text: Four published journal and conference papers, listed in reverse chronological order.
      count: 0
      # Curated newest-first order because Crossref provides only the year for
      # the IEEE Access article, while the conference records include full dates.
      sort_by: Weight
      sort_ascending: true
      filters:
        folders:
          - publications
        tags:
          - Peer-Reviewed
    design:
      view: publication-list
      columns: 1
      spacing:
        padding: ['3rem', '0', '2rem', '0']

  - block: collection
    content:
      title: Research Manuscripts Under Review
      text: Submitted to ICLR 2027. These manuscripts have not been accepted or published.
      count: 0
      sort_by: Weight
      sort_ascending: true
      filters:
        folders:
          - publications
        tags:
          - Under Review
    design:
      view: publication-list
      columns: 1
      spacing:
        padding: ['2rem', '0', '2rem', '0']

  - block: markdown
    content:
      text: |
        [View all publications on Google Scholar](https://scholar.google.com/citations?user=OcVajRwAAAAJ&hl=en)
    design:
      columns: '1'
      spacing:
        padding: ['1rem', '0', '2rem', '0']
---
