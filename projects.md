---
layout: singlePage
title: "Projects"
permalink: /projects/
description: 
nav: true
---
# Projects
Coming soon.

<html>
<style>
.grid-container {
  display: grid;
  padding-left: 25px;
  padding-right: 25px;
  grid-template-columns: 200px 200px 200px;
  grid-template-rows: 300px 300px 300px;
  grid-column-gap: 25px;
  grid-row-gap: 25px;
  border-top: 1px solid #dfdfdf;
  border-bottom: 1px solid #dfdfdf;
  border-left: 1px solid #dfdfdf;
  border-right: 1px solid #dfdfdf;
}
</style>

<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>
  <div class="grid-item">7</div>
  <div class="grid-item">8</div>
  <div class="grid-item">9</div>
</div>
</html>

<table class="table table-hover">
  {% for post in site.posts %}
    {% unless post.draft %}
    <tr>
      <td><a href="{{ post.url }}">{{ post.title }}</a></td>
      <td class="col-md-3" style="text-align: right;">{{ post.date | date: "%B %e, %Y" }}</td>
    </tr>
    {% endunless %}
  {% endfor %}
</table>