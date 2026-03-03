---
title: Welcome to the Feinberg Lab
type: landing

sections:
  - block: markdown
    id: about-full-image
    content:
      title: ''
      text: |
        <div class="banner-wrapper-black">
          <div class="full-width-bleed">
            <img src="/images/n7t_b.png" alt="NexGen 7T Banner">
          </div>
        </div>
    design:
      background:
        color: '#000000' # This sets the Hugo block background to black
      spacing:
        padding: ['0', '0', '0', '0']

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
          <p>David Feinberg's Lab at UC Berkeley, Department of Neuroscience, is improving spatial resolution and image quality in functional MRI and diffusion fibertrack imaging for neuroscience research and medical imaging. The Lab in collaboration with industrial partners continues to improve the MRI scanner hardware and pulse sequence designs for human neuroscience. Dr Feinberg proposed and led the development of the NexGen 7T MRI scanner, also known as the Siemens Terra 7T Impulse scanner which has the highest performance gradients and the highest channel count receiver system in 7T scanners. This ultra-high-field imaging platform achieves up to tenfold greater functional MRI resolution compared to conventional 7T systems—allowing researchers to localize brain activity and microstructure at the scale of cortical laminae and columnar neurocircuit organization. Making several hardware and software innovations, the lab team is able to achieve mesoscale imaging to detect abnormalities in disease states and trace brain networks with new precision, opening new possibilities for better understanding neurological disorders. Combining the ultra-high field magnet with extremely fast-switching high-amplitude gradients and novel layered high density receiver arrays, the NexGen 7T has unprecedented cumulative gains in SNR and resolution. The Lab has achieved a new regime for  diffusion imaging, at performance levels higher than any other scanner in the world for spatial and angular resolution in diffusion imaging of human brain. Through the NIH BRAIN funded dissemination project the Lab is collaborating with scientists and students from around the world in pioneering neuroscience research and translational clinical research.</p>
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