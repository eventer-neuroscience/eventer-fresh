+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

title = "FAQs"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  color = ""
  
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


+++



* **How can I cite Eventer in my work?** 
  * As you read this, a manuscript is in preperation. While the paper is being written, please cite as;  
  * *Winchester, G., Liu, S., Steele, O.G., Aziz, W. and Penn, A.C. (2020) Eventer. Software for the detection of spontaneous synaptic events measured by electrophysiology or imaging. http://doi.org/10.5281/zenodo.3991677*  
<br>
* **Why is my Eventer slow to load?**  
  * Eventer uses the Matlab runtime environment, which takes about as long as it takes for Matlab to load. In particular, Eventer tends to be slow to load for the first time following installation. Once Eventer has loaded, it should run fast so long as your computer has suitable specifications for running the [Matlab runtime](https://www.mathworks.com/products/compiler/matlab-runtime.html). It is not advisable to install Eventer or the Matlab runtime environment on a network drive since this will slow down the load time considerably.  
<br> 
* **What do i do with the error message `unable to locate file of variable 'orifile'`?** 
  * Please ensure that there are no files named `temp` on your filepath. Eventer is unable to function normally if this is the case. The file, `temp`, is filetype non-specific.   
  
<!-- 
## FAQ's to be answered ##
<br>
* **How can I load the ephysIO (`.phy`) file in Python?**
  * See here for your answer when i write it ...   
<br>  
* **Why does my data look funny when I use MATLAB's *load* command to load my `.phy` file?** 
  * See here for your answer when i write it ...  
<br>
--!>
