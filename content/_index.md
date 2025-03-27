---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
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

    design:
      css_class: text-gray-700
      background:
        color: white

      
  - block: collection
    id: papers
    content:
      title: Projects
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2



---
