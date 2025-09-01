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
  #- block: portfolio
    #id: projects
    #content:
    #  title: Research
    #design:
    #  columns: '2'
  - block: blank
    id: research
    content:
      title: Research
      text: |
        <section class="accordion">

        <details>
          <summary><strong>[Paper title 1]</strong></summary>
          <div class="abstract">
            [Paste abstract 1 here. You can use plain text or Markdown.]
          </div>
        </details>

        <details>
          <summary><strong>[Paper title 2]</strong></summary>
          <div class="abstract">
            [Abstract 2...]
          </div>
        </details>

        <details>
          <summary><strong>[Paper title 3]</strong></summary>
          <div class="abstract">
            [Abstract 3...]
          </div>
        </details>

        <!-- Add more <details> blocks as needed -->

        </section>
    design:
      columns: '1'

    
    
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: Shiny, Spatial Analysis, ML
          icon: r-project
          icon_pack: fab
        - name: Python
          description: oTree, Spatial Analysis, PyTorch
          icon: python
          icon_pack: fab
        #- name: Statistics
        #  description: 100%
        #  icon: chart-line
        #  icon_pack: fas
  
---
