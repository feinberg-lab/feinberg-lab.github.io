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
          - publication/manuscripts
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

  - block: collection
    id: abstracts
    content:
      title: |
        <h2 class="join-header">Recent Abstracts</h2>
        <div class="gold-divider"></div>
      subtitle: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      text: ''
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - publication/abstracts
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
---
