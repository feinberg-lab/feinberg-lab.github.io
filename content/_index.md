---
title: Welcome to the Feinberg Lab
type: landing

sections:
  - block: markdown
    id: about
    content:
      title: 'About'
      subtitle: ''
      text: |
        This site provides information about David Feinberg's neuroscience lab at UC Berkeley.
        
        ![NEXGEN-7T Team](/images/dwi.jpg)
        
        The research group investigates the fundamental principles of neuroscience...
    design:
      columns: '1'
      
  # BLOCK 1: Research Group Basics
  - block: markdown
    id: about
    content:
      title: ''
      subtitle: ''
      text: |
        <h2 class="join-header">About</h2>
        <div class="gold-divider"></div>
        
        <figure class="lab-basics-figure">
          <img src="/images/dwi.jpg" class="lab-basics-img">
          <figcaption>The NEXGEN-7T Team at UC Berkeley.</figcaption>
        </figure>

        <div class="lab-style-block">
        <p>This site provides information about David Feinberg's neuroscience lab at UC Berkeley. The research group investigates the fundamental principles of [Field]. Our research group combines [Method A] and [Method B] to solve challenges in [Specific Problem]. Etc</p>
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
      subtitle: '[All news >>](/news)'
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