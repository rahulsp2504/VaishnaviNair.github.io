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
    button:
      text: Download Résumé
      url: uploads/resume.pdf
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: purdue.jpg
      button:
        style: 'font-size: 5em; padding: 50px 70px; background-color: #78888a; color: red; border-radius: 5px;'
      biography:
        # Customize the style of your biography text
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
