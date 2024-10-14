---
title: Publications
cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 4

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""

# Filter on criteria
filters:
  tag: ''
  date: ''
  publication_type: ''
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
