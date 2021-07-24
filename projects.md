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
  grid-template-rows: 250px 250px 250px 250px;
  grid-column-gap: 15px;
  grid-row-gap: 15px;
}
.grid-item {
  border-radius: 5px;
/*  width: 225px;
  height: 250px; */
  border-top: 0px solid #d4d4d4;
  border-bottom: 0px solid #d4d4d4;
  border-left: 0px solid #d4d4d4;
  border-right: 0px solid #d4d4d4;
  box-shadow: 3px 4px 5px #d4d4d4;
}
div.grid-item>img {
  border-radius: 7px;
  border:0px;
  border-style: none;
  display: block;
}

div.grid-item>h5{
  text-align: center;

}

div.grid-item:hover{
   box-shadow: 7px 7px 7px #cccccc;
}

div.grid-item:hover>h5{
  color: #4582ec;
}


</style>

<div class="grid-container">
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/SomervilleBoardgame.png"> <h5> Optical tweezers to manipulate single cells </h5></div>
  <div class="grid-item"> <h5> Selecting single cells with microfluidics </h5></div>
  <div class="grid-item"> <h5> Amateur telescope making </h5></div>
  <div class="grid-item"> <h5> Low cost sickle cell diagnostics </h5></div>
  <div class="grid-item"> <h5> Feature matching across images </h5></div>
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