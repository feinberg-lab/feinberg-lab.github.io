---
title: Welcome to the Feinberg Lab
type: landing

sections:
  - block: markdown
    id: about-full-image  # Unique ID to target with CSS
    content:
      title: ''
      subtitle: ''
      text: |
        <div class="full-width-bleed">
          <img src="/images/n7t_b.png" alt="NexGen 7T Banner">
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0', '0', '0', '0'] # Forces the block to have zero internal spacing

  - block: markdown
    id: about
    content:
      title: ''
      text: |
        <div class="static-full-card">
          <h2 class="join-header">About</h2>
          <div class="gold-divider"></div>
        </div>
        <div class="lab-style-block">
          <p>Feinberg Lab at UC Berkeley... </p>
        </div>
    design:
      columns: '1'

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
---