---
# Leave the homepage title empty to use the site title
title: 'Jinho Kim'
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/CV.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: resume-experience
    content:
      username: me
  #- block: markdown
  #  content:
  #    title: '📚 My Research'
  #    subtitle: ''
  #    text: |-
  #      Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #      I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

  #      Please reach out to collaborate 😃
  #  design:
  #    columns: '1'
  #- block: collection
  #  id: papers
  #  content:
  #    title: Working Papers
  #    filters:
  #      folders:
  #        - publications
  #      featured_only: true
  #  design:
  #    view: card  # article-grid
  #    columns: 2
  - block: collection
    id: research
    content:
      title: Working Papers
      text: ''
      filters:
        folders:
          - working_papers
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: work-in-progress
    content:
      title: Work in Progress
      text: ''
      filters:
        folders:
          - work-in-progress
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: discussions
    content:
      title: Discussions
      filters:
        folders:
          - discussions
    design:
      view: citation # card
  #- block: collection
  #  id: teaching
  #  content:
  #    title: Teaching
  #    filters:
  #      folders:
  #        - teaching
  #  design:
  #    view: citation # card

  - block: markdown
    id: teaching
    content:
      title: Teaching Assistant
      text: |-

      
        <div class="h-6"></div>

        #### Ph.D. Macroeconomic Theory (2023–2026)

        <p class="flex flex-wrap gap-3">
          <a class="hb-attachment-link hb-attachment-link-large" href="/teaching/phd-macro/200E_Section_Week1_markov_process.pdf">Week 1 — Markov Process</a>
          <a class="hb-attachment-link hb-attachment-link-large" href="/teaching/phd-macro/200E_Section_Week2_bellman_linearization.pdf">Week 2 — Stochastic RBC Model, Linearization</a>
          <a class="hb-attachment-link hb-attachment-link-large" href="/teaching/phd-macro/200E_Section_Week3_blanchard_khan.pdf">Week 3 — Blanchard-Khan Condition</a>
          <a class="hb-attachment-link hb-attachment-link-large" href="/teaching/phd-macro/200E_Section_Week4_balanced_growth_path.pdf">Week 4 — Balanced Growth Path</a>
          <a class="hb-attachment-link hb-attachment-link-large" href="/teaching/phd-macro/200E_Section_Week6_investment_adjustment.pdf">Week 6 — RBC Extension: Investment Adjustment Cost</a>
          <a class="hb-attachment-link hb-attachment-link-large" href="/teaching/phd-macro/200E_Section_Week7_MIU.pdf">Week 7 — Money-in-Utility Model</a>
          <a class="hb-attachment-link hb-attachment-link-large" href="/teaching/phd-macro/200E_Section_Week8_MP_in_MIU.pdf">Week 8 — Monetary Policy in MIU Model</a>
          <a class="hb-attachment-link hb-attachment-link-large" href="/teaching/phd-macro/200E_Section_Week9_NewKeynesian.pdf">Week 9 — New Keynesian Model</a>
        </p>

        #### Intermediate Macroeconomics, Principles of Macro/Microeconomics, Money, Banks, and Financial Institutions (2021–2026)
  - block: markdown
    id: references
    content:
      title: References
      text: |-
        <div class="not-prose grid w-full grid-cols-1 gap-6 md:grid-cols-2">
          <div class="rounded-xl border border-gray-200 bg-white p-6 shadow-md dark:border-gray-700 dark:bg-gray-900">
            <div class="text-lg font-bold text-gray-900 dark:text-white">James Cloyne <span class="text-sm font-semibold text-gray-500 dark:text-gray-400">(Chair)</span></div>
            <div class="mt-2 text-base text-gray-600 dark:text-gray-300">Professor of Economics</div>
            <div class="text-base text-gray-600 dark:text-gray-300">University of California, Davis</div>
            <a class="mt-4 inline-block text-base font-semibold text-primary-600 underline dark:text-primary-400" href="mailto:jcloyne@ucdavis.edu">jcloyne@ucdavis.edu</a>
          </div>

          <div class="rounded-xl border border-gray-200 bg-white p-6 shadow-md dark:border-gray-700 dark:bg-gray-900">
            <div class="text-lg font-bold text-gray-900 dark:text-white">Òscar Jordà</div>
            <div class="mt-2 text-base text-gray-600 dark:text-gray-300">Professor of Economics</div>
            <div class="text-base text-gray-600 dark:text-gray-300">University of California, Davis</div>
            <a class="mt-4 inline-block text-base font-semibold text-primary-600 underline dark:text-primary-400" href="mailto:ojorda@ucdavis.edu">ojorda@ucdavis.edu</a>
          </div>

          <div class="rounded-xl border border-gray-200 bg-white p-6 shadow-md dark:border-gray-700 dark:bg-gray-900">
            <div class="text-lg font-bold text-gray-900 dark:text-white">Nicolas Caramp</div>
            <div class="mt-2 text-base text-gray-600 dark:text-gray-300">Assistant Professor of Economics</div>
            <div class="text-base text-gray-600 dark:text-gray-300">University of California, Davis</div>
            <a class="mt-4 inline-block text-base font-semibold text-primary-600 underline dark:text-primary-400" href="mailto:ncaramp@ucdavis.edu">ncaramp@ucdavis.edu</a>
          </div>

          <div class="rounded-xl border border-gray-200 bg-white p-6 shadow-md dark:border-gray-700 dark:bg-gray-900">
            <div class="text-lg font-bold text-gray-900 dark:text-white">Sanjay R. Singh</div>
            <div class="mt-2 text-base text-gray-600 dark:text-gray-300">Associate Professor of Economics</div>
            <div class="text-base text-gray-600 dark:text-gray-300">University of California, Davis</div>
            <a class="mt-4 inline-block text-base font-semibold text-primary-600 underline dark:text-primary-400" href="mailto:sjrsingh@ucdavis.edu">sjrsingh@ucdavis.edu</a>
          </div>
        </div>
  - block: markdown
    id: contact
    content:
      title: Contact Details
      text: |-
        <div class="h-4"></div>

        <p class="text-center">
          <strong>Email:</strong>
          <a href="mailto:jinho.kim.econ@gmail.com">jinho.kim.econ@gmail.com</a>
        </p>

  #- block: collection
  #  id: news
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: ''
      # Page type to display. E.g. post, talk, publication...
  #    page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
  #    count: 10
      # Filter on criteria
  #    filters:
  #      author: ''
  #      category: ''
  #      tag: ''
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ''
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
      # Choose a layout view
  #    view: card
      # Reduce spacing
  #    spacing:
  #      padding: [0, 0, 0, 0]

---
