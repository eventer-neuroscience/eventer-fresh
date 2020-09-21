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
+++

<div align="justify">

## Preload settings  
Choose your channel and split settings. Only some data formats allow for multiple recording channels, so unless you need to, the channel feature can be left at 1. Split should only be used if your data varies in length or if you want to split a continuous recording wave into smaller chunks for parallel processing.
{{< figure src="img/Screenshot 2020-08-18 at 16.09.13.png" title="Pre-load settings in Eventer" numbered="true" >}}


## Loading your data  
Choose which data you wish to analyse. Multiple data sets can be analysed at once. Eventer will merge these data sets together so ensure you are loading data that you want merged. To load multiple data sets to be merged, simply repeat the loading process shown below.
{{< figure src="img/Screenshot 2020-08-18 at 16.09.18.png" title="Loading your data in Eventer" numbered="true" >}}

## Visualising your data
Eventer includes a preview tab for immediate visualisation of your data upon loading. To inspect the data in more detail, the ‘Pop-up Graph’ should be used as shown here. This graph can then be zoomed and dragged to located individual events.
{{< figure src="img/Screenshot 2020-08-18 at 16.09.23.png" title="Visualising your data in Eventer" numbered="true" >}}

## Prefiltering your data
It is possible that excess noise is still present in your data that may not have been isolated during data acquisition. To help visualise data, Eventer enables the user to pre-filter their data through high- and low-pass filter cut offs. Shown here, a 1 kHz low-pass filter is applied to the data in the detection tab.
{{< figure src="img/Screenshot 2020-08-18 at 16.09.30.png" title="Pre-filtering your data in Eventer" numbered="true" >}}

## Defining your event template
In the template tab you can set a template event for the software to compare your data against. This can be set manually if the rise and decay parameters of your events are known, or can be done through opening the ‘Pop-up Graph’ as mentioned before and selecting the button highlighted here. This will allow the user to select two points; one before and one after the event of interest. The time constants will then be in the boxes below the highlighted button and should then be copied into boxes above before selecting the button ‘Apply to all waves’.
It is worth locating an event in the ‘Pop-up Graph’ before defining the time constants and that the sign of your events is correctly stated in the detection panel.
{{< figure src="img/Screenshot 2020-08-18 at 16.09.35.png" title="Defining your event template in Eventer" numbered="true" >}}

## Excluding regions from your analysis
It is possible that there are regions of your data that you want to be excluded from the analysis. For example, this could be a particularly noisy section of recording or the inclusion of a test pulse as shown here. To exclude these regions, open the exclude tab and regions to be excluded can either be manually typed in or selected using the highlighted button. Selecting this button will bring up cursors similar to the template selection window.
Screenshot 2020-08-18 at 16.09.40.png
{{< figure src="img/Screenshot 2020-08-18 at 16.09.40.png" title="Excluding regions from your analysis in Eventer" numbered="true" >}}

## Parallel Processing
If you wish to use parallel processing which will speed up analysis on newer computers, you can choose the number of workers. The limit of how many workers you can have is dependent on how many cores and threads your CPU has. After the worker number has been chosen, check the parallel box and wait for the workers to initialize.
{{< figure src="img/Screenshot 2020-08-18 at 16.09.45.png" title="Enabling parrellel processing in Eventer" numbered="true" >}}

## Running your analysis
Once the user is happy with the settings for their analysis, open the output tab and ensure the data will be outputted into the desired output format and saved to the appropriate location. By default this will create a folder named ‘eventer.output’ in the current working directory that the data was located. Choose which waves you would like stored in the analysis by either going through each wave individually and selecting/deselecting the store checkbox, or click the store all waves button. Unless a new output folder is specified for new analysis on the same dataset, it will be overwritten when performing new analysis.
Changing the box on the right from ‘Current’ to ‘Batch’ will tell Eventer that the analysis can be performed on the batch of waves stored, rather than solely on the current wave. If the user has not loaded multiple files or split the recording then ‘Current’ and ‘Batch’ will both be the same. Having confirmed these settings the user can hit ‘Run’ and the light will turn green indicating analysis is in progress.
{{< figure src="img/Screenshot 2020-08-18 at 16.09.50.png" title="Running your analysis in Eventer" numbered="true" >}}

## Accessing your results
After running the analysis, Eventer will open multiple figures. A quick summary of results is also available in the summary tab as shown here. The rest of your results will be saved in the root directory in the previously specified output folder.
{{< figure src="img/Screenshot 2020-08-18 at 16.09.55.png" title="Accessing your results in Eventer" numbered="true" >}}

# Training a machine learning model
Eventer also includes an option to enable users train a machine learning model against an exemplary set of data. To do this, open the detection tab and change the event criterion to ‘Machine Learning’ before ticking the ‘Training Mode’ tickbox. Running the analysis now will open up a window that will ask users to classify events as either events or not. A pop-up window will allow the user to also name their model. Move through the events selecting or deselecting events where appropriate until all events are classified then click complete.
When selecting whether an event is indeed actually an event, it is important that the green line shown above is exactly at the start of where you perceive the event to be otherwise the model may become inaccurate.
{{< figure src="img/Screenshot 2020-08-18 at 16.10.00.png" title="Training a machine learning model in Eventer" numbered="true" >}}

## Using your model
To then use the trained model on subsequent analysis, the user can then deselect the training mode and select load model in the detection tab. The trained model will be stored in the eventer output folder as a .mlm file as shown here. This model is now available for use on a new dataset, distinct from the set it was trained on. Upon completing your analysis with your machine learning model, you will be presenting with a plot showing the out-of-bag classification error which can briefly be described as a measure of the prediction error using bootstrap aggregating (bagging) to subsample data samples used for training. The prediction error should then stabilize well before reaching 128 trees (which is the default number of trees used by the implementation of Random Forests in Eventer).
{{< figure src="img/Screenshot 2020-08-18 at 16.10.05.png" title="Using your machine learning model in Eventer" numbered="true" >}}

</div>

