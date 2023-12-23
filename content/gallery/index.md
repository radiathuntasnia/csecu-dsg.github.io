---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
# widget: pages
# - block: markdown
content:
  # # Page type to display. E.g. project.
  page_type: markdown
  title: Best Paper Award
  subtitle: ''
  text: |-
    {{< gallery album="award" lightbox="true" resize_options="450x450" >}}
  design:
    columns: '1'
    # Toggle between the various page layout types.
    #   1 = List
    #   2 = Compact
    #   3 = Card
    #   5 = Showcase
    view: 3

gallery_item:
  - album: award
    image: ANC_best_paper_award.jpg
    caption: caption 1
#   - album: <ALBUM FOLDER>
#     image: <IMAGE 2 NAME>.jpg
#     caption: Write your image 2 caption here

---