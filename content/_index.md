---
# Leave the homepage title empty to use the site title
title:
date: 
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: page
    id: project-1  # Change to your project's ID or a custom identifier
    content:
      title: "Project 1 Title"  # The project's title
      subtitle: "Project 1 Subtitle"  # The project's subtitle
  - block: portfolio
    id: projects
    content:
      title: Research
    design:
      columns: '1'
      view: card
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
