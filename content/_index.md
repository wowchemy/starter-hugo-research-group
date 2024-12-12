---
# Leave the homepage title empty to use the site title
title:
date: 2023-10-24
type: landing

sections:


  - block: about.avatar
    id: home
    content:
      username: admin


  - block: people
    id: people
    content:
      title: 
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
          - Former Members
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true


  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      count: 5  
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation


  - block: collection
    id: posts
    content:
      title: Recent & Upcoming Seminars
      subtitle: ''
      text: 
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - event
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: 2
      # Choose single or dual column layout
      columns: '2'


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        
      # Contact (add or remove contact options as necessary)
      email: 
      phone:
      appointment_url:
      address:
        street: Departamento de Matemáticas, Universidad Carlos III de Madrid, Avda. de la Universidad 30
        city: 28911 Leganés
        region: (Madrid) Spain
        postcode: 
        country: 
        country_code: 
      directions: 
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '40.33177'
        longitude: '-3.76698'  
      contact_links:
        - icon: 
          icon_pack:
          name: 
          link: 
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: 
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
