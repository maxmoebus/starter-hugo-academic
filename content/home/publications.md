---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featured

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 25

title: Publications
subtitle: ''

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how much pages you would like to display (0 = all pages)
  count: 3
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  # Filter on criteria
  filters:
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 4
---

<!-- Add a dropdown for filtering by tags -->
<div>
  <label for="tag-filter">Filter by tag:</label>
  <select id="tag-filter" name="tag-filter" onchange="filterByTag(this.value)">
    <option value="">All</option>
    <option value="Perceived Health">Perceived Health</option>
    <option value="Interpretable Modeling">Interpretable Modeling</option>
    <option value="Mobile Health">Mobile Health</option>
  </select>
</div>

<script>
  function filterByTag(tag) {
    const urlParams = new URLSearchParams(window.location.search);
    if (tag) {
      urlParams.set('tag', tag);
    } else {
      urlParams.delete('tag');
    }
    window.location.search = urlParams.toString();
  }
</script>

 [Check out here](./publication/) for a complete list of my publications.
