---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Zhengtong Yang
        Personal homepage
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Zhengtong Yang Personal homepage desc
  - block: people
    content:
      title: Personal Introduction
    design:
      show_interests: false
      show_role: true
      show_social: true  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'


  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '5'

---
