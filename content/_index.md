---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      show_education_cards: false
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'My Research'
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
#   - block: collection
#     id: papers
#     content:
#       title: Featured Publications
#       filters:
#         folders:
#           - publications
#         featured_only: true
#     design:
#       view: article-grid
#       columns: 2
  - block: resume-experience
    id: education
    content:
      title: Education
      section: education
      username: admin
    design:
      date_format: 'January 2006'
  - block: markdown
    id: research
    content:
      title: Research
      subtitle: Current focus areas across instrumentation, algorithms, and machine learning.
      text: ''
  - block: research-highlight
    content:
      title: Studying Protoplanetary Disks with Generative Priors
      image: uploads/chara.png
      image_alt: CHARA Array Logo
      text: |-
        I currently work with Professor John Monnier at the University of Michigan, focusing on image reconstruction methods using generative
        priors. Image reconstruction in optical/infrared interferometry is an ill-posed inverse problem due to sparse sampling of the Fourier plane. This 
        necessitates the use of priors to regularize the solution. Until recently, analytic functions such as total variation have been used as priors, 
        but they often fail to capture the complex structures present in astronomical objects. My work explore the use of models such as normalizing flows and
        diffusion models as priors for interferometric image reconstruction. These models can learn complex distributions from large datasets, more effectibely encoding 
        our knowledge about the types of objects we expect to observe. By integrating these learned priors into the reconstruction process, we hope to resolve time variable
        substructures in protoplanetary disks, which may provide insights into planet formation, planet-disk interactions, and planet migration.
  - block: research-highlight
    content:
      title: PULSE-A - Space to Ground Optical Communications from a 3U CubeSat
      image: uploads/pulse-a.png
      image_alt: PULSE-A Logo
      text: |-
        I was a co-founder of the PULSE-A mission during my undergraduate studies at the University of Chicago.
        PULSE-A (Polarization-based Laser Satellite Experiment-A) is a 3U CubeSat mission designed to attempt polarization-based
        free-space optical communication between a satellite in low Earth orbit and a ground station. Designed by a team of undergraduate students,
        PULSE-A aims to increase the affordability and accessibility of space-to-ground optical communications, 
        which offer higher data rates and improved security compared to traditional radio frequency systems. It also serves as a risk reduction mission for a follow-up mission,
        PULSE-Q, which will demonstrate quantum key distribution from space. As co-founder, I played an instrumental role in mission concept development. I also co-authored several 
        grants, securing a launch opportunity through NASA's CubeSat Launch Initiative and $70,000 in confirmed funding.  I also co-authored a grant proposal to the NSF for $1,000,000
        to fund the PULSE-Q mission, which has been selected as a finalist and is currently under review. This has culminated in two conference publications so far.
  - block: research-highlight
    content:
      title: MAROON-X
      image: uploads/maroonx.jpg
      image_alt: MAROON-X Instrument. The vacuum chamber is shown.
      text: |-
        Prior to starting my PhD, I worked as an research assistant with Professor Jacob Bean at the University of Chicago on the MAROON-X
        high-resolution spectrograph for exoplanet detection. I focused on integrating the laser frequency comb into the calibration pipeline for MAROON-X,
        which would improve the long-term stability and precision of radial velocity measurements. This work culimated in my thesis, which detailed the calibration scheme 
        for both the Fabry-Perot etalon (which is currently in use) and the laser frequency comb. I also presented this work at the 245th AAS meeting in January 2025.
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
      sort_by: weight
      sort_ascending: true
    design:
      view: citation
  - block: resume-skills
    id: skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-languages
    id: languages
    content:
      title: Languages
      username: admin
#   - block: collection
#     id: talks
#     content:
#       title: Recent & Upcoming Talks
#       filters:
#         folders:
#           - events
#     design:
#       view: card
#   - block: collection
#     id: news
#     content:
#       title: Recent News
#       subtitle: ''
#       text: ''
#       # Page type to display. E.g. post, talk, publication...
#       page_type: blog
#       # Choose how many pages you would like to display (0 = all pages)
#       count: 5
#       # Filter on criteria
#       filters:
#         author: ''
#         category: ''
#         tag: ''
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#         publication_type: ''
#       # Choose how many pages you would like to offset by
#       offset: 0
#       # Page order: descending (desc) or ascending (asc) date.
#       order: desc
#     design:
#       # Choose a layout view
#       view: card
#       # Reduce spacing
#       spacing:
#         padding: [0, 0, 0, 0]
  - block: cta-card
    demo: false # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
