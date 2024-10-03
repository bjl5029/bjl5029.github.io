
---
# Leave the homepage title empty to use the site title
title: "what test"
date: 2024-10-01
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
        text: 소개.pdf
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  # Adding Experience section
  - block: collection
    content:
      title: 경험
      text: ""
      filters:
        folders:
          - experience
      design:
        view: article-list
        columns: 1
---
