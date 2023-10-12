---
# Leave the homepage title empty to use the site title
title:
date: 
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: projects
    content:
      title: Research
    design:
      columns: '2'
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 100%
          icon: r-project
          icon_pack: fab
        - name: Python
          description: 100%
          icon: python
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
  
---
