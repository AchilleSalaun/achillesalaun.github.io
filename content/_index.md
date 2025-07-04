---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: collection
    id: publications
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
      count: 0
    design: 
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - talk
    design:
      view: card
      columns: 1
  - block: markdown
    id: coffee
    content:
      title: 'Coffee Break ☕️'
      subtitle: ''
      text: |-
        Would you like us to meet around a cup of coffee or a glass of water?
        Here are some topics I am always happy to chat about!

        <table style="width:100%">
          <tr style="height:1em">
            <td style="width:80%;vertical-align:top">
              Naturally, we can chat about <strong>research</strong>.
              I would be glad to know more about your current works
              and answer any of your questions about mine
              (but you can already start by asking them there :point_right:
              {{< obfuscated_email "✉" >}}).
            </td>
            <td style="vertical-align:top"><img src="/media/science_mini.png"></td>
          </tr>
        </table>
        <table style="width:100%">        
          <tr>
            <td style="width:20%;vertical-align:top"><img src="/media/drawing_mini.png"></td>
            <td style="vertical-align:top">
              In my spare time, I love <strong>drawing</strong> on my pen tablet:
              you can have a look on my creations on Instagram :point_right:
              <a href="https://www.instagram.com/achillesalaun/">{{< icon name="brands/instagram"  pack="brand" >}}</a>!
              One of my dreams would be to draw my own comic book. Who knows, maybe one day?
            </td>
          </tr>
        </table>
        <table style="width:100%"> 
          <tr>
            <td style="width:80%;vertical-align:top">
              I used to do <strong>fencing</strong> at a competitive level. 
              I also enjoy running from time to time!
            </td>
            <td style="vertical-align:top"><img src="/media/fencing_mini.png"></td>
          </tr>
        </table>

    design:
      columns: '1'
---
