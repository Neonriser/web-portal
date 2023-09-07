---
layout: page.njk
title: Page not found
permalink: not_found.html #I deliberately typed the wrong page name, and the default 404 page shows up. I hope this solves the problem.
eleventyExcludeFromCollections: true
crumbs:
  - title: Page not found
---

The url: <code id="url"></code> doesn't seem to exist in the server.

[Go back home](/)

<script>
  var x = document.URL;
  document
    .getElementById("url")
    .innerHTML = x;
</script>
