---
# Leave the homepage title empty to use the site title
title: Emerson Hamer
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Tableu
     #      description: 90%
          icon: salesforce
          icon_pack: fab
        - name: Cloud Computing 
   #       description: 100%
          icon: cloud
          icon_pack: fas
        - name: Python
   #       description: 10%
          icon: python
          icon_pack: fab
        - name: Overleaf
   #       description: 10%
          icon: overleaf
          icon_pack: ai
        - name: Github
   #       description: 10%
          icon: github
          icon_pack: fab
        - name: ArcGIS
   #       description: 10%
          icon: globe
          icon_pack: fas
        - name: SQL 
   #       description: 100%
          icon: database
          icon_pack: fas
 #- block: experience
  # content:
  #    title: Experience
  #    # Date format for experience
  #    #   Refer to https://wowchemy.com/docs/customization/#date-format
  #    date_format: Jan 2006
  #    # Experiences.
  #    #   Add/remove as many `experience` items below as you like.
  #    #   Required fields are `title`, `company`, and `date_start`.
  #    #   Leave `date_end` empty if it's your current employer.
  #    #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #    items:
  #      - title: CEO
  #        company: GenCoin
  #        company_url: ''
  #        company_logo: org-gc
  #        location: California
  #        date_start: '2021-01-01'
  #        date_end: ''
  #        description: |2-
  #            Responsibilities include:
  #
  #            * Analysing
  #            * Modelling
  #            * Deploying
  #      - title: Professor of Semiconductor Physics
  #        company: University X
  #        company_url: ''
  #        company_logo: org-x
  #        location: California
  #        date_start: '2016-01-01'
  #        date_end: '2020-12-31'
  #        description: Taught electronic engineering and researched semiconductor physics.
  #  design:
  #    columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/7d95bf029b987da486a46f29965d2a4ee5378ee0
          date_end: ''
          date_start: '2023-01-10'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: Introduction to Version Control with Git
          url: ''
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/b544e3d7a867f9876a766327f1d0784109d8a4ba
          date_end: ''
          date_start: '2023-02-02'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: Intermediate Regression with statsmodels in Python
          url: ''
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/a1df7236fc1e484d7a6ea113581163a3432440bc
          date_end: ''
          date_start: '2023-01-13'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: Understanding Cloud Computing
          url: ''
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/7d95bf029b987da486a46f29965d2a4ee5378ee0
          date_end: ''
          date_start: '2023-08-21'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: Introduction to SQL
          url: ''
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/2937e4ed2941ad5e68a138525b22fe141a5f7471
          date_end: ''
          date_start: '2023-09-08'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: Introduction to Tableau
          url: '' 
 #        - certificate_url: https://www.datacamp.com/statement-of-#accomplishment/course/7d95bf029b987da486a46f29965d2a4ee5378ee0
 #         date_end: ''
  #        date_start: '2023-09-08'
  #        description: ''
   #       organization: DataCamp
  #        organization_url: https://www.datacamp.com
   #       title: Introduction to Tableau
  #        url: ''
  #  design:
  #    columns: '2'
  #- block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
  #    # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #    # Choose how many pages you would like to offset by
  #    offset: 0
  #    # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
  #    # Choose a layout view
  #    view: compact
  #    columns: '2'
  #- block: portfolio
  #  id: projects
  #  content:
  #    title: Projects
  #    filters:
  #      folders:
  #        - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #    default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
  #    buttons:
  #      - name: All
  #        tag: '*'
  #      - name: Deep Learning
  #        tag: Deep Learning
  #      - name: Other
  #        tag: Demo
  #  design:
  #    # Choose how many columns the section has. Valid values: '1' or '2'.
  #    columns: '1'
  #    view: showcase
  #    # For Showcase view, flip alternate rows?
  #    flip_alt_rows: false
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: true
  #  design:
  #    columns: '2'
  #    view: citation
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
    
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      #text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: emerson.hamer@emory.edu
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: >-
          R. Randall Rollins 
          1516 Clifton Road
        city: Atlanta
        region: GA
        postcode: '30322'
        country: United States
        country_code: US
      #directions: R. Randall Rollins (R433)
      #office_hours:
       # - 'Monday 10:00 to 13:00'
       # - 'Wednesday 09:00 to 10:00'
      #contact_links:
        #- icon: twitter
         # icon_pack: fab
          #name: DM Me
          #link: 'https://twitter.com/Twitter'
       # - icon: skype
       #   icon_pack: fab
       #   name: Skype Me
       #   link: 'skype:echo123?call'
       # - icon: video
       #   icon_pack: fas
       #   name: Zoom Me
       #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
     # form:
      #  provider: netlify
      #  formspree:
       #   id:
       # netlify:
          # Enable CAPTCHA challenge to reduce spam?
         # captcha: false
   # design:
    #  columns: '2'
---
