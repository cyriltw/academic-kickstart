+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 50  # Order that this section will appear.

title = "Research Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

[design.background]
    # Background gradient.
    gradient_start = "#4bb4e3"
    gradient_end = "#2b94c3"
    
    # Background image.
    image = "exp.jpg"  # Name of image in `static/img/`.
    image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
    image_position = "center"  # Options include `left`, `center` (default), or `right`.
    image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

    # Text color (true=light or false=dark).
    text_color_light = true
# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Research Assistant"
  company = "Rochester Institute of Technology"
  company_url = "https://www.rit.edu/"
  company_logo = "rit.svg"
  location = "Rochester"
  date_start = "2018-08-01"
  date_end = ""
  description = """
  Responsibilities include:
  
  * Working on research for predicting human disagreements on natural language social media datasets.
  * Build research pipelines for deploying on Google Cloud using Python Machine Learning stack and MongoDB.
  * Presented work at [ECAI 2020](../publication/weerasooriya-2020/). 
  """

[[experience]]
  title = "Adjunct Lecturer"
  company = "Rochester Institute of Technology"
  company_url = "https://www.rit.edu/"
  company_logo = "rit.svg"
  location = "Rochester, NY"
  date_start = "2020-05-01"
  date_end = "2020-08-31"
  description = """
  * Taught CS635 - Introduction to Machine Learning virtually.
  """
[[experience]]
  title = "Intern Research Assistant"
  company = "HEALS Project (part of IBM AI Horizon) at Rensselaer Polytechnic Institute"
  company_url = "https://www.rpi.edu/"
  company_logo = "rpi.svg"
  location = "Troy, NY"
  date_start = "2019-05-01"
  date_end = "2019-08-31"
  description = """
  * Research based on natural language processing and information retrieval.
  * Conducted research on aggregating food related data sources for food knowledge graph, which is used with IBM Watson.
  * The tool was able to generate the nutritional content per FDA guidelines from a crowdsourced recipe.
  """
[[experience]]
  title = "Tech Lead"
  company = "LKEMR"
  company_url = "https://www.rpi.edu/"
  company_logo = "rpi.svg"
  location = "Sri Lanka"
  date_start = "2018-03-01"
  date_end = ""
  description = """
  * Research based on natural language processing and information retrieval.
  * Conducted research on aggregating food related data sources for food knowledge graph, which is used with IBM Watson.
  * The tool was able to generate the nutritional content per FDA guidelines from a crowdsourced recipe.
  """
+++
