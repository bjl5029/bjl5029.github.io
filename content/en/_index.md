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
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: experience
    content:
      title: Experience
      subtitle: ''
      text: ''
      page_type: author
      count: 1
      filters:
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
---
