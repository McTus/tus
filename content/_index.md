---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: About Me
    username: admin
  id: about
  
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Job Market Paper
  design:
    columns: "2"
    view: compact
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      
    title: Working Paper
  design:
    columns: "2"
    view: compact
- block: collection
  content:
    filters:
      folders:
      - event
    title: Work-in-Progress
  design:
    columns: "2"
    view: compact
  id: talks
title: null
type: landing
---
