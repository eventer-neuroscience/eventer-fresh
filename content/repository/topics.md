+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true # Activate this widget? true/false
weight = 2 # Order that this section will appear.

title = "Model Repository"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  # To show the tags in the posts choose "post" folder
  page_type = "post"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  #[[content.filter_button]] # "All is too much content"
  #  name = "All"
  #  tag = "*"
  
  [[content.filter_button]]
    name = "All"
    tag = "*"
    
  [[content.filter_button]]
    name = "mIPSC"
    tag = "mIPSC"
  [[content.filter_button]]
    name = "mEPSC"
    tag = "mEPSC"
  [[content.filter_button]]
    name = "NMDAR"
    tag = "NMDAR"
  [[content.filter_button]]
    name = "AMPAR"
    tag = "AMPAR"   
  [[content.filter_button]]
    name = "GABA"
    tag = "GABA"    
    
  [[content.filter_button]]
    name = "Calcium Imaging"
    tag = "Calcium Imaging"  
  [[content.filter_button]]
    name = "Electrophysiology"
    tag = "Electrophysiology" 
    
  [[content.filter_button]]
    name = "Acute Brain Slice"
    tag = "Acute Brain Slice"
    
  [[content.filter_button]]
    name = "Organotypic Slice Culture"
    tag = "Organotypic Slice Culture"
[[content.filter_button]]
    name = "Cell Culture"
    tag = "Cell Culture"  
    
  [[content.filter_button]]
    name = "Other"
    tag = "Other"
    
[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 2

  # For Showcase view, flip alternate rows?
  flip_alt_rows = true

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
+++



