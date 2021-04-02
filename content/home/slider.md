---
# Slider widget.
widget: "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless: true  # This file represents a page section.
active: true  # Activate this widget? true/false
weight: 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height: ""

# Slides.
# Duplicate an `[[item]]` block to add more slides.

item:
  - title: PhD student at University of Glasgow
    content: 'Tentative research title: Geo-demographic Dynamics of Settlements Using Historical Maps'
    align: right
    overlay_color: '#333'  # An HTML color value.
    overlay_img: university-of-glasgow-280.png # Image path relative to your `static/img/` folder.
    overlay_filter: 0.5  # Darken the image. Value in range 0-1. 
  - title: UrbanOccupationsOETR ERC-funded  Research Project
    content: '+3 Years experience as GIS Specialist and Research Fellow at Koç University'
    align: center
    overlay_color: '#555'  # An HTML color value.
    overlay_img: EU_ERC_KU_Merged_Logo.png  # Image path relative to your `static/img/` folder.
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
  - title: "Barcın Höyük Excavation"
    content: "Development of a 2.5D Spatiotemporal model"
    align: "left"  # Choose `center`, `left`, or `right`.
  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: "#666"  # An HTML color value.
    overlay_img: BH_model1.PNG  # Image path relative to your `static/img/` folder.
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Click here for the working model
    cta_url: 'https://pgerrits.com/publication/2016/barcin2016_cityengine/'
    cta_icon_pack: fas
    cta_icon: external-link-square-alt
---