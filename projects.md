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
  border-radius: 10px;
  width: 225px;
  height: 300px; 
  border-top: 1.5px solid #000000;
  border-bottom: 1.5px solid #000000;
  border-left: 1.5px solid #000000;
  border-right: 1.5px solid #000000;
}
.grid-item img{  
  border: 0px
  height: 75%; 
  width: 100% 
}
.img { 
  border: 0px
  height: 75%; 
  width: 100% 
}
</style>

<div class="grid-container">
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/SomervilleBoardgame.png"> </div>
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