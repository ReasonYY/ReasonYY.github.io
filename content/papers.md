---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  # - block: resume-experience
  #   content:
  #     username: admin
  #   design:
  #     # Hugo date format
  #     date_format: 'January 2006'
  #     # Education or Experience section first?
  #     is_education_first: false
  - block: collection
    id: papers
    content:
      title: Peer Reviewed Journals
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: [20,0,0,0]
  # - block: collection
  #   id: working
  #   content:
  #     title: Preprints
  #     text: ""
  #     filters:
  #       folders:
  #         - preprints
  #       exclude_featured: false
  #   design:
  #     view: citation
  #     spacing:
  #       padding: [0,0,0,0]
  - block: collection
    id: progress
    content:
      title: Ongoing Projects
      text: ""
      filters:
        folders:
          - inprogress
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: [0,0,0,0]
  # - block: resume-awards
  #   content:
  #     title: Awards
  #     username: admin
  # - block: resume-languages
  #   content:
  #     title: Languages
  #     username: admin
---
