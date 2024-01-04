---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      image:
        filename: uw-white.png
      cta_note:
      text: |-
        <br><p style="font-size:1em">Change is a cross-campus collaboration bringing together faculty and students from the University of Washington with the wider community to collaborate on and explore the challenges of developing technology in the context of positive social change. The change organization seeks to make connections between researchers, outside organizations, and the public to inspire the development of new capabilities aligned with the interests of those most in need.</p>
    design:
      background:
        gradient_end: '#4b2e83'
        gradient_start: '#4b2e83'
        text_color_light: true
  #- block: about.avatar
  #  id: about
  #  content:
      # Choose a user profile to display (a folder name within `content/authors/`)
  #    username: admin
      # Override your bio text from `authors/admin/_index.md`?
  #    text:
  #- block: logos
  #  content:
  #    title: Partners
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
        featured_only: true
      sort_by: "Date"
      sort_ascending: false
    design:
      columns: '2'
      view: modified_compact
  - block: mailing
    content:
      title: Contact
      text: |-
        {{<p>}}Please subscribe to our (mailing list)[https://dubber.cs.washington.edu/mailman/listinfo/change]. View archives at mail-archive.com{{</p>}}
      # Contact (add or remove contact options as necessary)
---
