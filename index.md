---
layout: base.njk
title: Your Name | Resume # not relevant if only printing to PDF; this is the title of the browser tab
name: Your Name

contactDetails:
  # include any means of contact you like
  - url: mailto:youremail@example.com
    text: youremail@example.com
  - url: tel:+12345678912
    text: (234) 567-8912
  - url: https://linkedin.com
    text: LinkedIn
  - url: https://github.com
    text: GitHub

experience:
  sectionTitle: Experience
  entries:
    # include any roles or projects you like
    - employer: Big Company
      position: Software Engineer
      dates: 2023 - 2024
      accomplishments:
        - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    - employer: Cool Startup
      position: Software Engineer
      dates: 2021 - 2022
      accomplishments:
        - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    - employer: Previous Career
      position: Administrative Assistant
      dates: 2016 - 2021
      accomplishments:
        - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        - Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

education:
  sectionTitle: Education
  entries:
    - name: State University
      descriptionLines:
        - School of Learning Things
        - BA, Things
    - name: Training Program
      descriptionLines:
        - Certificate, Thing You Trained In

skills:
  sectionTitle: Technologies and Tools
  entries:
    - category: Languages
      contents:
        - TypeScript
        - JavaScript
        - HTML
        - CSS
        - Python
    - category: Databases
      contents:
        - PostgreSQL
        - MySQL/MariaDB
        - SQLite
        - MongoDB
    - category: Industry Skills
      contents:
        - Making convincing sample data
        - Being serious about business
---
