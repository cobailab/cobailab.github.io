---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Laboratory of Computational Biophysics and AI-driven Bioengineering
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The <strong><u>Co</u></strong>mputational <strong><u>B</u></strong>iophysics and <strong><u>AI</u></strong>-driven Bioengineering Laboratory (**CoBAI Lab**) develops computational and AI-driven approaches to understand, model, and engineer biomolecular systems.
  
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
        publication_type: 'manuscript'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |-
        <div class="row align-items-stretch" style="background-color:#eef4f7; border-radius:18px; overflow:hidden; margin:0;">
          <div class="col-md-7 p-0">
            <img src="/uploads/suatbanner.jpg" alt="CoBAI Lab research team" style="width:100%; height:100%; min-height:360px; object-fit:cover; display:block;">
          </div>
          <div class="col-md-5 d-flex align-items-center">
            <div style="width:100%; padding:clamp(2rem, 5vw, 4rem); text-align:left;">
              <div style="font-size:0.8rem; font-weight:700; letter-spacing:0.12em; color:#587083; margin-bottom:0.8rem;">OUR PEOPLE</div>
              <h2 style="margin-top:0; margin-bottom:1rem;">Meet the CoBAI Team</h2>
              <div style="font-size:1.05rem; line-height:1.7; color:#4a5560;">Our group brings together ideas from computational biophysics, molecular modeling, artificial intelligence, and biomolecular engineering.</div>
              <a href="./people/" class="btn btn-primary px-4 py-3 mt-4">Explore our team →</a>
            </div>
          </div>
        </div>
    design:
      columns: '1'
---
