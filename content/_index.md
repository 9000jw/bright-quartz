---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: '4rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: hero
    content:
      title: Templergraben 39
      text: Evangelisches Studentenwohnheim
      primary_action:
        text: Bewirb dich fürs Wohnheim
        url: bewerbung/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "indigo"
        image:
          # Add your image background to `assets/media/`.
          filename: blaueshaus.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false

  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: skills
    content:
      title: Skills & Hobbies
      username: admin
  - block: awards
    content:
      title: Awards
      username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---
