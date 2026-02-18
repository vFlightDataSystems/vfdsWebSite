---
title: Home
---

# vfdsWebSite
hello world

[Link to delme](test/delme.md)

<input id="search-input" type="search" placeholder="Search docs…" style="width:100%;padding:.6rem;font-size:1rem;">
<ul id="results-container"></ul>

<script src="https://cdn.jsdelivr.net/npm/simple-jekyll-search@1.11.0/dest/simple-jekyll-search.min.js"></script>
<script>
  SimpleJekyllSearch({
    searchInput: document.getElementById('search-input'),
    resultsContainer: document.getElementById('results-container'),
    json: '{{ "/search.json" | relative_url }}',
    searchResultTemplate: '<li><a href="{url}">{title}</a></li>',
    noResultsText: '<li>No results</li>',
    limit: 20
  });
</script>
