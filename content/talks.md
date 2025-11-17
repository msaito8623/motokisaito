---
title: 'Talks'
date: 2025-01-29
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: collection
    content:
      title: Upcoming Talks
      filters:
        folders:
          - upcoming_talks
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Past talks
      filters:
        folders:
          - past_talks
    design:
      view: citation
---
