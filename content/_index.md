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
  - block: biography
    content:
      username: admin
      # Place the button content first to appear above the biography
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        filename: purdue.jpg
      biography:
        # Move biography styling below the button
        style: 'text-align: justify; font-size: 0.8em;'
      button:
        style: 'font-size: 1.2em; padding: 10px 20px; background-color: #78888a; color: white; border-radius: 5px;'
      
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
