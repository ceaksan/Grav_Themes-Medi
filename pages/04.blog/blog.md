---
title: Blog
content:
    items:
        '@taxonomy.category': blogitem
    limit: 5
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
an_example_text_field: '5'
simplesearch:
    route: /search
    template: simplesearch_results
    filters:
        category: blog
    filter_combinator: and
---

Vivamus at magna non nunc tristique rhoncus. Aliquam nibh ante, egestas id dictum a, commodo luctus libero.
