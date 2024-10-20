---
# Leave the homepage title empty to use the site title
title: Home
date: 2023-08-16
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: Python
  #         description:
  #         icon: python
  #         icon_pack: fab
  #       - name: Java
  #         description: 
  #         icon: java
  #         icon_pack: fab
  #       - name: Linux
  #         description:
  #         icon: linux
  #         icon_pack: fab
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  - block: collection
    id: publications
    content:
      title: Papers
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    id: projects
    content:
      title: Academic Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: TaRDIS - Trustworthy And Resilient Decentralised Intelligence For Edge Systems
          company: NOVA Laboratory for Computer Science and Informatics
          company_url: 'https://nova-lincs.di.fct.unl.pt/'
          company_logo: tardis
          location: Portugal
          date_start: '2024-07-15'
          date_end: ''
          description: Member of the <a target="_blank" href="https://www.project-tardis.eu/">TaRDIS project</a>, working on the self-management of distributed sysyems. TaRDIS’s primary goal is to significantly ease the complexity and reduce the effort of building correct and efficient heterogeneous swarms. TaRDIS focuses on supporting the correct and efficient development of applications for swarms and decentralised distributed systems, by combining a novel programming paradigm with a toolbox for supporting the development and execution of applications.
        - title: NOVA LINCS Researcher
          company: NOVA Laboratory for Computer Science and Informatics
          company_url: 'https://nova-lincs.di.fct.unl.pt/'
          company_logo: novalincs
          location: Portugal
          date_start: '2024-04-09'
          date_end: ''
          description: Member of the NOVA LINCS Computer Systems Group at NOVA School of Science and Technology | FCT NOVA, conducting my PhD and researching the self-management of distributed systems.
        - title: Alexa Prize TaskBot Challenge 2
          company: NOVA School of Science and Technology | FCT NOVA
          company_url: 'https://fct.unl.pt'
          company_logo: alexa_prize
          location: Portugal
          date_start: '2022-07-14'
          date_end: '2023-10-03'
          description: Team member of team TWIZ, winning team in Amazon's Alexa Prize TaskBot Challenge 2, working on visual dialogue and coherent image generation. [Alexa Prize TaskBot Challenge](https://www.amazon.science/alexa-prize/taskbot-challenge) is a university challenge focused on developing multimodal (voice, text, and touch) conversational agents that assist customers in completing tasks requiring multiple steps and decisions.
        - title: NOVA LINCS Researcher
          company: NOVA Laboratory for Computer Science and Informatics
          company_url: 'https://wiki.novasearch.org/'
          company_logo: novalincs
          location: Portugal
          date_start: '2022-07-14'
          date_end: '2023-12-21'
          description: Member of the NOVA LINCS Multimodal Systems Group at NOVA School of Science and Technology | FCT NOVA. Conducted my MSc dissertation, entitled "Visual Dialogue for Open Tasks", focused on multimodal systems, visual dialogue, and coherent image sequence generation.
    design:
      columns: '2'
  - block: experience
    id: experience
    content:
      title: Work Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Intern
          company: Hypnotic Digital Agency
          company_url: 'https://hypnoticagency.com/'
          company_logo:
          location: Portugal
          date_start: '2021-03-01'
          date_end: '2021-07-31'
          description: Frontend Developer (Vue.js).
    design:
      columns: '2'
  - block: accomplishments
    id: awards
    content:
      title: Awards and Others
      date_format: Jan 2, 2006
      items:
        - title: PhD Studentship
          organization: FCT - Fundação para a Ciência e Tecnologia
          organization_url: 'https://www.fct.pt'
          url: 'https://www.fct.pt/en/concursos/concurso-bolsas-de-doutoramento-2024-linha-de-candidatura-geral-1-1'
          date_start: '2025-01-01'
          date_end: '2029-01-01'
          description: To fulfil its aim of promoting a national public policy for advanced training with social relevance and impact, the Fundação para a Ciência e a Tecnologia, I.P. (FCT) opens a Call for granting PhD studentships.
        - title: 1st place in the Alexa Prize TaskBot Challenge 2
          organization: Amazon Science
          organization_url: 'https://www.amazon.science/'
          url: 'https://www.amazon.science/alexa-prize/taskbot-challenge/2022'
          date_start: '2023-10-03'
          description: Member of the winning team TWIZ in the Alexa Prize TaskBot Challenge 2.
        - title: NOVA Young Talent Award
          organization: NOVA School of Science and Technology | FCT NOVA
          organization_url: 'https://fct.unl.pt'
          certificate_url: 'certificates/nova_award.pdf'
          date_start: '2021-05-18'
          description: The "NOVA Young Talent Awards" honor the students which stood out in the 1st year of their Bachelor Degree or Integrated Masters at NOVA. The award is given to the students with highest average in the first year of their respective course.
  - block: accomplishments
    id: volunteering
    content:
      title: Volunteering
      date_format: Jan 2, 2006
      items:
        - title: ACM Multimedia 2022
          organization: ACM Multimedia
          organization_url: 'https://2022.acmmm.org/'
          certificate_url: 'certificates/acmmm22_certificate.pdf'
          date_start: '2022-10-10'
          date_end: '2022-10-14'
          description: Volunteer at ACM Multimedia 2022.
        - title: DisCoTec 2023
          organization: DisCoTec
          organization_url: 'http://www.discotec.org/2023/'
          certificate_url: 'certificates/discotec_certificate.pdf'
          date_start: '2023-06-19'
          date_end: '2023-06-23'
          description: Volunteer at DisCoTec 2023.
        - title: EXPO Faculdade de Ciências e Tecnologias 2023
          organization: NOVA School of Science and Technology | FCT NOVA
          organization_url: 'https://fct.unl.pt'
          certificate_url: 'certificates/expo_certificate.pdf'
          date_start: '2023-04-19'
          description: Volunteer at EXPO Faculdade de Ciências e Tecnologias 2023.
        - title: EXPO Faculdade de Ciências e Tecnologias 2024
          organization: NOVA School of Science and Technology | FCT NOVA
          organization_url: 'https://fct.unl.pt'
          #certificate_url: 'certificates/expo_certificate.pdf'
          date_start: '2024-04-10'
          description: Volunteer at EXPO Faculdade de Ciências e Tecnologias 2024.
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text:
      # Contact (add or remove contact options as necessary)
      email: j.bordalo@campus.fct.unl.pt
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      contact_links:
        # - icon: twitter
        #   icon_pack: fab
        #   name: DM Me
        #   link: 'https://twitter.com/Twitter'
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
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
