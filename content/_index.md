---
title: Welcome to the Feinberg Lab
type: landing

sections:
  - block: markdown
    id: about
    content:
      title: ''
      subtitle: ''
      text: |
        <div class="static-full-card">
          <h2 class="join-header">About</h2>
          <div class="gold-divider"></div>
        </div>
        <div class="lab-style-block">
          <p>Feinberg Lab at UC Berkeley..</p>
        </div>
      design:
        columns: '1' # Set to '2' if you want the title on the left and text on the right

  - block: markdown
    id: about
    content:
      title: ''
      subtitle: ''
      text: |
        <div class="static-full-card">
          <figure class="lab-basics-figure">
            <img src="/images/NexGen7Tscanner.jpg" class="static-card-img">
          </figure>
        </div>
        <div class="lab-style-block">
          <p>Scanner..</p>
        </div>
      design:
        columns: '1' # Set to '2' if you want the title on the left and text on the right

  - block: markdown
    id: about
    content:
      title: ''
      subtitle: ''
      text: |
        <div class="static-full-card">
          <figure class="lab-basics-figure">
            <img src="/images/projects.png" class="static-card-img">
          </figure>
        </div>
        <div class="lab-style-block">
          <p>Layer fMRI..</p>
        </div>
      design:
        columns: '1' # Set to '2' if you want the title on the left and text on the right

  - block: markdown
    id: about
    content:
      title: ''
      subtitle: ''
      text: |
        <div class="static-full-card">
          <figure class="lab-basics-figure">
            <img src="/images/dwi.jpg" class="static-card-img">
          </figure>
        </div>
        <div class="lab-style-block">
          <p>Diffusion..</p>
        </div>
      design:
        columns: '1' # Set to '2' if you want the title on the left and text on the right

  # BLOCK 2: Recent News
  - block: collection
    id: news
    content:
      title: |
        <h2 class="join-header">Recent News</h2>
        <div class="gold-divider"></div>        
      subtitle: '[All news >>](news/)'
      filters:
        folders:
          - news
      count: 5
    design:
      view: citation
      columns: '1'
      background:
        color: '#f9f9f9' # Optional: light gray to separate sections
---
