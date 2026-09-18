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
          <p>David Feinberg's Lab in the Department of Neuroscience at UC Berkeley is pushing fMRI and diffusion imaging into new realms to study neurocircuitry. Currently using the most powerful 7T scanner for fMRI, the lab is studying cortical layer-level circuitry in the human brain, identifying previously unidentified brain circuits. This is achieved by improving spatial resolution and image quality in functional MRI and diffusion fiber-tracking imaging for neuroscience research and medical imaging.</p>
          <p>The Lab, in collaboration with industrial partners, continues to improve MRI scanner hardware and pulse sequence designs for human neuroscience. Dr. Feinberg proposed the design and led the development of the Next Generation (NexGen) 7T MRI scanner, also known as the Siemens Terra Impulse scanner. The Berkeley NexGen 7T scanner combines, for the first time, an ultra-high field with ultra-strong gradients and features the highest channel count (128-channel) receiver system in 7T scanners to increase cortical SNR and whole-brain image acceleration. This scanner achieves up to tenfold greater functional MRI resolution compared to conventional 7T systems - allowing researchers to localize brain activity and microstructure at the scale of cortical laminae and columnar neurocircuit organization.</p>
          <p>Making several hardware and software innovations, the lab is able to achieve mesoscale imaging to detect abnormalities in disease states and trace brain networks with new precision, opening new possibilities for a better understanding of neurological disorders. Combining the ultra-high field magnet with extremely fast-switching high-amplitude gradients and novel layered high-density receiver arrays, the NexGen 7T has unprecedented gains in image SNR and spatial resolution important for studying brain circuitry.</p>
          <p>The Lab, in collaboration with UCSF scientists, is using the NexGen scanner to increase precision in imaging research on several neurological diseases, including Alzheimer's disease, mild cognitive impairment (MCI), Parkinson's disease, multiple sclerosis, brain tumors, and epilepsy. The Lab has achieved a new regime for diffusion imaging, operating at performance levels higher than any other scanner in the world for spatial and angular resolution in diffusion imaging of human brain. Additionally, through an NIH BRAIN Initiative funded dissemination grant, the Lab is supporting and collaborating in over 20 projects around the world with scientists and students in pioneering neuroscience research and translational clinical research.</p>
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