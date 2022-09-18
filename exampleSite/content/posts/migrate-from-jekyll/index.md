---
date: 2014-03-10
displayInMenu: false
displayInList: true
draft: false
title: Migrate to Hugo from Jekyll
resources:
- name: featuredImage
  src: "yan-ots-257617-unsplash.jpg"
  params:
    description: "Colorful buildings alongside a body of water"
---

## Move static content to `static`
Jekyll has a rule that any directory not starting with `_` will be copied as-is to the `_site` output. Hugo keeps all static content under `static`. You should therefore move it all there.