---
widget: portfolio
headless: true

# ... Put Your Section Options Here (title etc.) ...
title: Work and fun
subtitle: 

weight: 20

content:
  # Choose which content to display in the widget
  filters:
    # Folders to display content from
    folders:
      - news
    # Uncomment below to only show content with specific tags:
#    tags:
#      - Machine Learning
    # Uncomment below to exclude content with specific tags:
#    exclude_tags:
#      - preface    
    # Uncomment below to show specific Hugo Page kinds
    kinds:
      - page
#      - section

  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: false

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:
    - name: All
      tag: "all_social"
    - name: 2020
      tag: 2020_social
    - name: 2021
      tag: 2021_social
    - name: 2022
      tag: 2022_social

  # Default filter toolbar button (e.g. 0 corresponds to the first `filter_button` instance above)
  filter_default: 0

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'
  # Choose a listing view
  view: masonry
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
