---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: "Portfolio"
subtitle: "A showcase of my work in Data Science, Machine Learning, and Analytics."

content:
  # Page type to display.
  page_type: project

  # Default filter index (e.g. 0 = first filter button below)
  filter_default: 0

  # Filter toolbar for categories
  filter_button:
    - name: All
      tag: '*'
    - name: Data Analytics
      tag: Analytics
    - name: Machine Learning
      tag: ML
    - name: Computer Vision
      tag: CV
    - name: Natural Language Processing
      tag: NLP
    - name: Backend & Automation
      tag: Backend
    - name: AI Applications
      tag: AI

design:
  columns: '2'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: { padding: [0, 0, 0, 0] }
---
