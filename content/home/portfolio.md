---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio
content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Sort the projects by their file names in ascending order.
  sort_by: "title"
  
  # Filter toolbar (optional)...

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: ''
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Unban Analysis
      tag: Unban Analysis
    - name: Urban Planning
      tag: Urban Planning
    - name: Unban Design
      tag: Unban Design


design:
  columns: '1'
  view: masonry
  flip_alt_rows: false
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---
