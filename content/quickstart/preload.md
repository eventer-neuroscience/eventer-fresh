+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 2  # Order that this section will appear.

title = "Pre-Load Settings"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  text_color_light = false
  # Background color.
  color = "#FFFFFF	"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  #text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]



[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""

### this is alert note that should be used in the markdown part of the document
#{{% alert note %}}
#This homepage section is an example of adding [elements](https://sourcethemes.com/academic/docs/writing-markdown-latex/) to #the [*Blank* widget](https://sourcethemes.com/academic/docs/widgets/).

#Backgrounds can be applied to any section. Here, the *background* option is set give an *image parallax* effect.
#{{% /alert %}}

image:
  placement: 1
  caption: "Photo by [Academic](https://github.com/eventer-neuroscience/eventer-fresh/blob/master/content/quickstart/img/Screenshot%202020-08-18%20at%2016.09.13.png/)"
  focal_point: "Center"
  preview_only: false
  alt_text: An optional description of the image for screen readers.
+++

<br>

<div align="justify">
Here are some notes on your preload settings ... 

Here is a picture of your pre load settings ...  

{{< figure src="img/Screenshot 2020-08-18 at 16.09.13.png" title="A caption" numbered="true" >}}

</div>

