---
template: post
title: Huy Nguyen
slug: h2o7
draft: false
date: 2019-08-18T14:09:34.602Z
description: test
category: test
tags:
  - test tag
---
```
backend:
  name: github
  repo: huynguyen2071991/h2o7_blog

media_folder: "static/media"
public_folder: "/media"

collections:
  - name: "posts"
    label: "Posts"
    folder: "content/posts"
    create: true
    slug: "{{year}}-{{month}}-{{day}}-{{slug}}"
    fields:
      - {label: "Template", name: "template", widget: "hidden", default: "post"}
      - {label: "Title", name: "title", widget: "string"}
      - {label: "Slug", name: "slug", widget: "string"}
      - {label: "Draft", name: "draft", widget: "boolean", default: true}
      - {label: "Publish Date", name: "date", widget: "datetime"}
      - {label: "Description", name: "description", widget: "text"}
      - {label: "Category", name: "category", widget: "string"}
      - {label: "Body", name: "body", widget: "markdown"}
      - {label: "Tags", name: "tags", widget: "list"}

  - name: "pages"
    label: "Pages"
    folder: "content/pages"
    create: true
    slug: "{{slug}}"
    fields:
      - {label: "Template", name: "template", widget: "hidden", default: "page"}
      - {label: "Title", name: "title", widget: "string"}
      - {label: "Slug", name: "slug", widget: "string"}
      - {label: "Draft", name: "draft", widget: "boolean", default: true}
      - {label: "Body", name: "body", widget: "markdown"}
```

<!-- blank line -->

<figure class="video_container">

  <iframe width="560" height="315" src="https://www.youtube.com/embed/6YhqQ2ZW1sc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</figure>

<!-- blank line -->
