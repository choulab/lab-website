+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Projects"
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
  
  [[content.filter_button]]
    name = "all"
    tag = "*"
  
  [[content.filter_button]]
    name = "active"
    tag = "active"
    
  [[content.filter_button]]
    name = "past"
    tag = "past"

#  [[content.filter_button]]
#    name = "Workshop"
#    tag = "workshop"
  
#  [[content.filter_button]]
#    name = "Course"
#    tag = "course"
    
#  [[content.filter_button]]
#    name = "Book"
#    tag = "book"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

  # Toggle between the various page layout types.
  #   1 = List
  #   3 = Card
  #   5 = Showcase
  view = 3

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

We engineer DNA and proteins to create self-assembling molecular devices for biological applications. Our current projects focus on two sets of applications:<br>

- technologies to explore, bind, and re-wire cell surface receptors and downstream signaling pathways
- cell-free molecular computing technologies for portable molecular diagnostics and information processing

These technologies are composed of engineered DNA and protein molecules, which have been programmed to self-assemble via specific rules and structures for carrying out user-defined tasks. Below you will find a list of our current and past projects (and yes, Leo enjoys coming up with cryptic project code names):