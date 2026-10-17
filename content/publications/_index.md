---
title: Publications
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
      view: citation
      columns: 1

  - block: collection
    content:
      title: Manuscripts Under Review
      text: Submitted manuscripts that have not been accepted or published.
      count: 0
      sort_by: Weight
      sort_ascending: true
      filters:
        folders:
          - publications
        tags:
          - Under Review
    design:
      view: citation
      columns: 1
---
