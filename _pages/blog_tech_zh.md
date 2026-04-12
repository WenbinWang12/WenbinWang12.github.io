---
layout: default
permalink: /zh/blog_tech/
title: 技术
nav: false
lang: zh
translation_key: blog-tech
blog_name: 洞见栈
blog_description: 记录技术探索，也记录对未来的想象。
pagination:
  enabled: true
  collection: posts
  permalink: /zh/blog_tech/page/:num/
  per_page: 5
  sort_field: date
  sort_reverse: true
  trail:
    before: 1
    after: 3
---

{% include blog_tech_content.liquid %}
