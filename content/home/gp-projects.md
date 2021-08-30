---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: slider

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 15

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 5000
height: 600px

item:
  - title: Galactic Polymath Projects
    content:
      <br>
      **galacticpolymath.com:** Check out our main site to find the latest *free* lessons based on current research.  

    # Choose `center`, `left`, or `right` alignment.
    align: left
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.

    overlay_img: 'gp-landing-hero.jpg'  # Image path relative to your `assets/media/` folder
    img_position: 50%
    overlay_filter: 0.4  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Visit the Site
    cta_url: 'https://galacticpolymath.com'
    cta_icon_pack: 'custom'
    cta_icon: 'gp_bubble'
    cta_font_col: '#cb1f8e'

  - title: Galactic Polymath Projects
    content:
      <br>
      **galacticEdTools:** an R package to support K-16 education and scicomm. Functions for a variety of things, including making evolutionary trees very easily.
    align: left
    overlay_color:
    overlay_img: 'panther_phylogeny.jpg'
    img_position: '40% 60%'
    overlay_filter: 0.6
    cta_url: 'https://galacticpolymath.github.io/galacticEdTools/'
    cta_label: 'Check it Out'
    cta_font_col: '#cb1f8e'

  - title: Galactic Polymath Projects
    content:
      <br>
      **Standard X:** a compilation of the leading academic standards in the US in 4 subjects—math, ELA, science, and social studies. Can you believe they've never been combined into a single spreadsheet before?!
    align: left
    overlay_color: ''
    overlay_img: 'graph-paper.jpg'
    img_position: '10% 80%'
    overlay_filter: .1
    cta_url: 'https://galacticpolymath.github.io/standardX/'
    cta_label: 'Check it Out'
    cta_font_col: '#cb1f8e'

---
