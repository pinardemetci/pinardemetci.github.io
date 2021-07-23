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
  grid-template-columns: 225px 225px 225px 225px;
  grid-template-rows: 300px 300px 300px 300px;
  grid-column-gap: 15px;
  grid-row-gap: 15px;
}
.grid-item {
  border-top: 1px solid #dfdfdf;
  border-bottom: 1px solid #dfdfdf;
  border-left: 1px solid #dfdfdf;
  border-right: 1px solid #dfdfdf;
}
 .img { max-height: 100%; max-width: 50% }
</style>

<div class="grid-container">
  <div class="grid-item">
    <div class="img"> <img src="images/cat3.jpeg" alt="Cat"> </div>
  1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>
  <div class="grid-item">7</div>
  <div class="grid-item">8</div>
  <div class="grid-item">9</div>
  <div class="grid-item">10</div>
  <div class="grid-item">11</div>
  <div class="grid-item">12</div>
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