---
title: 'Publications'
type: landing

sections:
  - block: collection
    id: publications
    content:
      title: |
        <h2 class="join-header">Select Publications</h2>
        <div class="gold-divider"></div>
      subtitle: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      text: ''
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - publication
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      show_publication: true
      show_authors: true
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Weight'
      sort_ascending: true
    design:
      # Choose a listing view
      view: custom-compact
      # Choose single or dual column layout
      columns: '1'
      spacing:
        padding: ['20px', '0', '0', '0'] # [Top, Right, Bottom, Left]

  - block: markdown
    id: scholar-footer
    content:
      title: ''
      subtitle: ''
      text: |
        <div class="scholar-container">
          <p style="margin: 0;">
            <i class="ai ai-google-scholar" style="color: #003262; font-size: 0.9rem; vertical-align: middle; margin-right: 5px;"></i> 
            For a full list of publications, visit 
            <a href="https://scholar.google.com/citations?user=uaUKPpoAAAAJ&hl=en" target="_blank" rel="noopener" style="color: #003262; font-weight: bold;">Google Scholar</a>.
          </p>
        </div>
    design:
      columns: '1'
      background:
        color: '#ffffff'
      spacing:
        padding: ['0', '0', '0', '0']

  - block: markdown
    id: nexgen-info
    content:
      title: ''
      text: |
        <h2 class="join-header">Recent Abstracts</h2>
        <div class="gold-divider"></div>
        <style>
          /* Ensures the image doesn't overflow the new narrow width */
          #nexgen-info img {
            max-width: 100% !important;
            height: auto;
          }
        </style>
        <div class="lab-style-block">
        <p>Whole-brain, cerebral blood volume weighted imaging optimized for the study of cortical networks on NexGen 7T scanner. Alexander J. Beckett, Suvi Häkkinen, Erica B. Walker, Oleksandr Khegai, An T. Vu, Renzo Huber, David Feinberg. ISMRM, 2026.</p>

        <p>Studying cortical networks using whole brain cerebral blood volume weighted imaging on the NexGen 7T. Alexander Beckett, Erica B Walker, Suvi Häkkinen, Oleksandr Khegai, An Vu, Renzo Huber, David Feinberg. OHBM, 2026.</p>

        <p>Accelerated 3D Zoomed GRASE for Mesoscale fMRI using Self-Supervised Reconstruction (DeepGRASE). Hyunseung RYU, Suvi Häkkinen, Alexander Beckett, Erica Walker, David A Feinberg, Suhyung Park. OHBM, 2026.</p>

        <p>Whole-brain, cerebral blood volume weighted imaging of cortical networks using the Next Generation (NexGen) 7T scanner. Alexander J. Beckett, Suvi Häkkinen, Erica B. Walker, Oleksandr Khegai, An T. Vu, Renzo Huber, David Feinberg. ISMRM, 2026.</p>

        <p>Functional imaging of hippocampal layers using VASO on the Next Generation (NexGen) 7T. Suvi Häkkinen, Alexander J. Beckett, Erica Walker, Renzo Huber, David A. Feinberg. ISMRM, 2025.</p>

        <p>Functional imaging of hippocampal layers using VASO on the Next Generation (NexGen) 7T. Alexander Beckett, Suvi Häkkinen, Erica Walker, Renzo Huber, David A. Feinberg. ISMRM Joint Workshop of the Ultra-High Field MR & Brain Function Study Groups, 2025.</p>

        <p>Whole-brain, cerebral blood volume weighted imaging of cortical networks using the Next Generation (NexGen) 7T scanner. Erica B. Walker, Alexander J. Beckett, Suvi Häkkinen, An Vu, Renzo Huber, & David Feinberg. SfN, 2025.</p>

        <p>Development of GRASE Pulse Sequence with larger field of view for mesoscale functional MRI on the Next Generation (NexGen) 7T scanner. Alexander J. Beckett, Suhyung Park, Suvi Häkkinen, Erica Walker, An Vu, David A. Feinberg. ISMRM, 2025.</p>
        </div>

        <!---
        <div style="display: flex; justify-content: center; width: 100%;">
        {{< figure src="projects.png" style="width: 80%;" >}}
        </div>
        -->
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '10px', '0']
---
