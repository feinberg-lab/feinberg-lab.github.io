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
          <p>Dr. David Feinberg’s Lab at UC Berkeley Department of Neuroscience is pioneering the integration of advanced MRI hardware, pulse sequence design, and neuroscience applications to push human brain imaging to unprecedented resolution. The lab led development of the NexGen 7T MRI scanner, an ultra-high-field platform that achieves up to tenfold greater functional MRI resolution compared to conventional 7T systems—allowing researchers to localize brain activity and microstructure at the scale of cortical laminae and columnar neurocircuit organization. By combining high-performance gradient coils, dense receiver arrays, and innovative pulse sequences, the team enables mesoscale imaging that can detect abnormalities or trace brain networks with new precision, opening transformative possibilities for understanding of neurological disorders.</p>
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