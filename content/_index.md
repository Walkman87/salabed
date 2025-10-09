---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-09-26
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: experience
    id: clin_exp
    content:
      title: Clinical Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:

        - title: Consultant Cardiac Radiologist
          company: Sheffield Teaching Hospitals
          company_logo: nhs
          location: Sheffield
          date_start: 2024-07-01
          description: |2-
          
            Cardiac MRI level 3 accreditation - SCMR
            Cardiac CT level 3 accreditation - BSCI
          

        - title: Advanced Cardiothoracic Imaging Fellowship
          company: Royal Papworth Hospital
          company_logo: nhs
          location: Cambridge
          date_start: 2023-06-01
          date_end: 2023-12-01
          description: |2-
            
            Clinical Supervisor: Dr Bobby Agrawal
            Academic Supervisor: Dr Jonathan Weir-McCall

        - title: Cardiothoracic Radiology Training
          company: Sheffield Teaching Hospitals
          company_logo: nhs
          location: Sheffield
          date_start: 2019-10-01
          date_end: 2023-06-01
          
        - title: Core Radiology Training
          company: Sheffield Teaching Hospitals
          company_logo: nhs
          location: Sheffield          
          date_start: 2014-09-01
          date_end: 2019-10-01
          description: |2-
          
            ST4 Acute and general CT, Oncology imaging, Ultrasound-guided intervention
            ST3 Chest, Uro & Gyneacological, Paediatric and Vascular radiology
            ST2 Neuroradiology, Gastro, MSK, Breast and Nuclear imaging
            ST1 Plain radiography, Ultrasound, CT, Fluoroscopy

        - title: Clinical Foundation Training
          company: Buckinghamshire Healthcare Trust
          company_logo: nhs
          location: Aylesbury, High Wycombe & Amersham          
          date_start: 2013-02-01
          date_end: 2014-09-01
          description: Cardiology including coronary care unit, heart failure and valve clinics

    design:
      columns: '2'
      view: compact

      
  - block: experience
    id: res_exp
    content:
      title: Research Experience
      items:
        - title: Senior Clinical Research Fellow
          company_logo: uos
          location: Sheffield             
          company: University of Sheffield
          date_start: 2024-07-01
          date_end: null
          description: Innovating technology to auto-report medical imaging and simplify them

        - title: NIHR Clinical Lecturer in Radiology
          company_logo: uos
          location: Sheffield             
          company: University of Sheffield
          date_start: 2022-08-01
          date_end: 2024-06-30
          description: Implementing AI applications in clinical practice

        - title: Wellcome Trust Research Fellow in Cardiac MRI
          company_logo: uos
          location: Sheffield            
          company: University of Sheffield
          date_start: 2019-10-01
          date_end: 2022-08-01
          description: |2-    
            Data scientist of the ASPIRE cardiac MRI and CT database
    
            Helped train, validate and audit deep learning cardiac MRI segmentation
    
            Applied machine learning in cardiac MRI to predict diagnosis and prognosis         

        - title: NIHR Academic Clinical Fellow in Radiology
          company_logo: uos
          location: Sheffield            
          company: University of Sheffield
          date_start: 2014-09-01
          date_end: 2019-10-01
          description: Performing and evaluating diagnostic accuracy studies in radiology

        - title: Cochrane Systematic Reviewer
          company_logo: coc          
          company: Cochrane Heart
          date_start: 2010-01-01
          date_end: null   


    design:
      columns: '2'
      
      
      
  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: '2025-02-01'
          description: 'Flagship national programme for digital health'
          icon: nhs
          organization: NHS England
          title: Topol Digital Fellowship 
        - certificate_url: https://www.daad.de/en/the-daad/postdocnet/fellows/fellows/#Alabed
          date_end: ''
          date_start: '2023-11-25'
          description: 'Excellence in AI Research'
          icon: daad
          organization: DAAD
          title: AI-NET Fellowship 
          url: https://www.daad.de/en/the-daad/postdocnet/fellows/fellows/
        - certificate_url: https://nhsparliamentaryawards.co.uk/2023-winners/
          date_end: ''
          date_start: '2023-07-05'
          description: Future of NHS Award for developing & clinically implementing automated cardiac segmentation
          icon: nhs
          organization: NHS
          title: NHS Parliamentary Awards
          url: https://nhsparliamentaryawards.co.uk/2023-winners/
        - certificate_url: https://digitalawards.hsj.co.uk/winners-2023#DigitalInnovatoroftheYear
          date_end: ''          
          date_start: '2023-06-01'
          description: 'Finalist for the HSJ Digital Innovator of the Year Award'
          icon: hsj
          organization: HSJ
          title: 'Digital Innovator of the Year'
          url: https://digitalawards.hsj.co.uk/winners-2023#DigitalInnovatoroftheYear          
        - certificate_url: https://www.medipexawards.co.uk/previous-entries/medipex-nhs-innovation-awards-2022/#panela1
          date_end: ''
          date_start: '2022-11-01'
          description: 'Winner of the Medipex NHS Innovation Award for Using Artificial Intelligence to improve patient services'
          icon: medipex
          organization: Medipex
          title: 'NHS Innovation Award'
          url: https://www.medipexawards.co.uk/previous-entries/medipex-nhs-innovation-awards-2022/#panela1
        - certificate_url: https://www.rcrglobalconference.com/speakers-2023/
          date_end: ''
          date_start: '2022-11-25'
          description: 'Winner of the Oral Presentation Prize at the Global RCR Conference in Dubai'
          icon: rcr
          organization: RCR
          title: Oral Abstract Winner at RCR Global - Dubai
          url: https://www.rcrglobalconference.com/speakers-2023/
        - certificate_url: https://pubs.rsna.org/doi/full/10.1148/radiol.229002
          date_end: ''
          date_start: '2021-12-03'
          description: For developing and validating AI cardiac image segmentation
          icon: rsna
          organization: RSNA
          title: RSNA Trainee Research Prize
          url: https://pubs.rsna.org/doi/full/10.1148/radiol.229002
        - certificate_url: ''
          date_end: ''          
          date_start: '2018-09-01'
          description: 'For evaluating economic evaluation of diagnostic MRI examination'
          icon: rcr
          organization: RCR
          title: 'George and Vera Ansell Radiology Research Prize'         
        - certificate_url: https://www.rcr.ac.uk/career-development/awards-honours/awards-for-research/the-constance-thornton-fellowship/
          date_end: ''
          date_start: '2017-11-01'
          description: 'For performing diagnostic accuracy meta-analyses '
          icon: rcr
          organization: RCR
          title: 'Constance Thornton Award for Radiology Research'
          url: https://www.rcr.ac.uk/career-development/awards-honours/awards-for-research/the-constance-thornton-fellowship/
    design:
      columns: '2'
        
  - block: portfolio
    id: projects
    content:
      title: AI Research Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: "*"
        - name: SHAIPS
          tag: SHAIPS
        - name: PyKale
          tag: PyKale  
        - name: HeartTalk
          tag: HeartTalk
        - name: MIRACLE
          tag: MIRACLE
        - name: AI in CMR
          tag: AI in CMR                   
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Full Publications List
      text: |-
        {{% callout note %}}
        For the full publications list see [Google Scholar](https://scholar.google.com/citations?user=7G4XAxYAAAAJ&hl=en).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
      
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'

  
---
