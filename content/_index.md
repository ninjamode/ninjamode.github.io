---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: |
        About us
        <br>
        {{< figure src="logo_hex-petrol.png" caption="" >}}
      subtitle: HEX Lab
      text: |
        ## Imagineering novel languages for the communication between humans (and machines).
        <br>

        Our research is centered around the understanding, design, development, and evaluation of computing solutions and human-machine interfaces that improve the way we interact with, work with, and communicate through machines. A majority of our research considers AI driven Extended Reality user interfaces in the context of physical and mental health, such as Virtual-, Mixed- or Augmented Reality systems. Examples of these are assistive technologies for medical procedures or systems to assess and diagnose pathologies and disorders.

        To do so, we strive for foundational, translational, and radical scientific contributions with high methodological and experimental quality. Our research is inspired by multiple disciplines, including but not limited to Computer Science, Psychology, Design, Medicine, and Neuroscience. We incorporate methods from these disciplines, such as computer vision, computer graphics, artificial intelligence, and user-centered design in a broad methodological bandwidth to support our research goals. We closely interact with partners from medicine and industry to incorporate different perspectives.
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

      
  - block: collection
    id: news
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '2'
  

  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Principal Investigators
        - Researchers
        - Grad Students
        - Administration
        - Visitors
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: true
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: false


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: ''
      # Contact details - edit or remove options as needed
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: Trogerstrasse 10
        city: Munich
        postcode: '81675'
        country: Germany
        country_code: DE
      directions: Find us on the third floor.
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/rothnroll'
      # Automatically link email and phone or display them just as text?
      autolink: true
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '48.1363964'
        longitude: '11.6023856'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'

---