+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "500px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Chou Lab at the University of Toronto"
  content = "We program DNA to create nanoscale devices that help us manipulate and dissect biological systems<br>(Image courtesy of Dr. Rasmus Sorensen)"
  align = "left"

  #overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/factory-1400x500.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.

  cta_label = "Learn More"
  cta_url = "/about#projects"
  cta_icon_pack = "fas"
  cta_icon = "search"

[[item]]
  title = "Where we are"
  content = "Our lab is located at the University of Toronto, in the heart of the city, within walking distance to the MaRS innovation centre and the University Hospitals"
  align = "left"

  #overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/cityscape-1400x500.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.2 # Darken the image. Value in range 0-1.

  cta_label = "Visit Us"
  cta_url = "/contact"
  cta_icon_pack = "fas"
  cta_icon = "map-marked"

[[item]]
  title = "Programmable gene circuits"
  content = "Our DNA-powered gene networks are being used to build portable molecular computers and operating systems"
  align = "left"

  #overlay_color = "#333"  # An HTML color value.
  overlay_img = "headers/T7GRN-1400x500.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.3  # Darken the image. Value in range 0-1.

  cta_label = "Learn More"
  cta_url = "/about#projects"
  cta_icon_pack = "fas"
  cta_icon = "search"

[[item]]
  title = "Multi-disciplinary team"
  content = "We work at the interface of chemistry, biology, engineering, and computer science"
  align = "left"

  #overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/laboratory-1400x500.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.3  # Darken the image. Value in range 0-1.

[[item]]
  title = "We are hiring"
  content = "Are you curious, driven, passionate, and innovative?"
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/UofTEng-1400x500.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.3  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Join Us"
  cta_url = "/join"
  cta_icon_pack = "fas"
  cta_icon = "graduation-cap"

+++