---
description: An example site for hugo-theme-gallery. Images from Unsplash.

title: Hugo Gallery
resources:
menus:
  main:
    name: Home
    weight: -1
# sub-galleries on list pages are sorted by date and weight (descending)
cascade:
  build:
    publishResources: true # do not include full images. Also disable download
---