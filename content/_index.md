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
          <p>David Feinberg’s Lab at UC Berkeley, Department of Neuroscience, is pioneering advanced MRI scanner hardware, designing pulse sequence for human neuroscience applications to increase the spatial-temporal resolution in brain imaging. Dr. Feinberg proposed and led the development of the 7T MRI scanner, also known as the Siemens Terra 7T Impulse scanner with currently the highest performance gradients and the highest channel count receiver system in a 7T scanner. This ultra-high-field imaging platform achieves up to tenfold greater functional MRI resolution compared to conventional 7T systems—allowing researchers to localize brain activity and microstructure at the scale of cortical laminae and columnar neurocircuit organization. By combining high-performance gradient coils, denser receiver coil arrays, and innovative pulse sequences, the lab team enables mesoscale imaging down to a few hundred microns to detect abnormalities in disease states and trace brain networks with new precision, opening new possibilities for better understanding neurological disorders. In diffusion imaging the scanner also  has cumulative increases in SNR by combining ultra-high field with extremely fast-switching high-amplitude gradients and novel layered receiver arrays together pushes  diffusion fiber-track imaging into a new regime, currently higher than any other scanner in the world for encoding higher spatial and anglular resolution. Through the NIH BRAIN Initiative funded dissemination project  the Lab is collaborating with scientists and students from around the world in pioneering neuroscience and translational clinical research.</p>
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