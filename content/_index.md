---
title: Home
title_before: bt
title_after: at
description: Description
description_before: db
description_after: da


sections:
  - type: section_hero
    template: section_hero
    title: Find your favourite casino, game or bonus
    section_id: hero
    image: https://casino.guru/images/homepage-bg.jpg
    # content: >-
    #   in the biggest and most accurate online casino database in the world
    # actions:
    #   - type: action
    #     template: action
    #     label: Get Started
    #     url: /docs
    #     style: primary
  - type: card_main_hero
    template: card_main_hero
    col_number: three
    grid_items:
      - type:  casino
        template: card_main_hero
        title: Casinos
        content: 
        actions:
          - type: action
            template: action
            label: Look at all
            url: /casino
            style: link
      - type:  game
        template: card_main_hero
        title: Games
        content: 
        actions:
          - type: action
            template: action
            label: Let's play
            url: /game
            style: link
      - type:  bonus
        template: card_main_hero
        title: Bonuses
        content: 
        actions:
          - type: action
            template: action
            label: Find better
            url: /bonus
            style: link

  - type: section_casinos_main
    template: section_casinos_main
    title: Top Casinos

  - type: section_games_main
    template: section_games_main
    title: Casino Games to play for free
    mode: light

  - type: section_bonuses_main
    template: section_bonuses_main
    title: New Bonuses


  - type: section_grid
    template: section_grid
    section_id: features-two-col
    col_number: two
    grid_items:
      - type: grid_item
        template: grid_item
        title: Site info
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla, fringilla tortor at, pulvinar orci.
        actions:
          - type: action
            template: action
            label: Learn More
            url: /info
            style: link
      - type: grid_item
        template: grid_item
        title: Other related information
        content: >-
          Donec lobortis velit sed suscipit lobortis. Ut non quam metus. Nullam
          a maximus mi. Quisque justo nunc, sollicitudin euismod euismod at,
          tincidunt ut tellus. Vivamus rhoncus mattis varius.
        actions:
          - type: action
            template: action
            label: Learn More
            url: /other
            style: link

            
  - type: section_cta
    template: section_cta
    title: Subscribe for lates info
    section_id: cta
    subtitle: Check when appear new bonuses, casinos, games and artilces...
    actions:
      - type: action
        template: action
        label: Subscribe for newsletter
        url: /docs/getting-started/installation
        style: primary

  - type: section_content
    template: section_content
    title: Fruitful Partnership. Outstanding Accomplishments
    section_id: text-no-img
    content: >-
      Become an SlotsBrain affiliate and benefit from an award-winning online casino review platform. For years, we've been constantly accomplishing our partner's goals in terms of professional companionship and effectiveness.
    actions:
      - type: action
        template: action
        label: Get Started
        url: /other/affiliate
        style: primary
layout: advanced
---
