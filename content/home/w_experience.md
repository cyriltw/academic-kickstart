+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 60  # Order that this section will appear.

title = "Related Experience"
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
  title = "Tech Lead"
  company = "LKEMR - Cloud-based Electronic Medical Record System"
  company_url = "http://lkemr.com/"
  company_logo = "lkemr.png"
  location = "Sri Lanka"
  date_start = "2018-03-01"
  date_end = ""
  description = """
Collaborative project with the Faculty of Medicine, and Colombo North Teaching Hospital, Sri Lanka.
Tools used - PHP, MySQL, HTML, CSS, and UNIX. Python for data mining. Hosted on DigitalOcean and AWS.
  * Web based electronic patient record management system, tailored for Sri Lanka using PHP backend, and MySQL database. 
  * EMR currently holds records for over 1,000 patients across several cities in Sri Lanka.
  * Currently been used to identify potential patients with COVID-19, as it is the only EMR widely used in Sri Lanka. 
  * The work also contributes to open sourced EMR Project, Open-EMR.
  * Research work published in NITC 2019 and workshop organizing committee for WONCA 2020.
  """
+++
