+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 70  # Order that this section will appear.

title = "Code and Data"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"


[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  


[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""



  # overlay_color = "#333"  # An HTML color value.
  # overlay_img = ""  # Image path relative to your `static/img/` folder.
  # overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
# Voronoi-Metrics:


+++

* [Dataset and Tools](https://github.com/V-Sense/VR_user_behaviour) for the paper of "Do Users Behave Similarly in VR? Investigation of the Influence on the System Design", ACM TOMM 2020.
* [Tools](https://github.com/cozcinar/VI_VMAF_4_360) for "Voronoi-based Objective Quality Metrics for Omnidirectional Video", QoMEX 2019.
* [Source code](https://github.com/V-Sense/360SR) for the paper of "Super-resolution of Omnidirectional Images Using Adversarial Learning", MMSP 2019.
* [Dataset](https://github.com/V-Sense/360AudioVisual) for the paper of "Towards generating ambisonics using audio-visual cue for virtual reality", ICASSP 2019.
* [Tools](https://github.com/cozcinar/optimalTiles) for the paper of "Visual Attention-Aware Omnidirectional Video Streaming Using Optimal Tiles for Virtual Reality", JETCAST 2019.
* [Dataset](https://github.com/cozcinar/omniAttention) for the paper of "Visual Attention in Omnidirectional Video for Virtual Reality Applications", QoMEX 2018.
