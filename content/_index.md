---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: button # New button block
    content:
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      button:
        style: 'font-size: 1.2em; padding: 10px 20px; background-color: #78888a; color: white; border-radius: 5px;'
  
  - block: biography # Biography block below button
    content:
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
      
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
      title: Skills
      username: admin
  - block: awards
    content:
      title: Publications
      username: admin
  - block: languages
    content:
      title: Languages
      username: admin
---
