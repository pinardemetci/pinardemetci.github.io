---
layout: singlePage
title: "Projects"
permalink: /projects/
description: 
nav: true
---
# Projects
I've had the opportunity to work on a number of engineering, science, and modeling projects. Here, you can browse a selection of them:

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
  border-top: 0px solid #cccccc;
  border-bottom: 0px solid #cccccc;
  border-left: 0px solid #cccccc;
  border-right: 0px solid #cccccc;
  box-shadow: 3px 4px 5px #cccccc;
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
   box-shadow: 10px 10px 10px #bbbbbb;
}

div.grid-item:hover>h5{
  color: #4582ec;
}


</style>

<div class="grid-container">
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/SomervilleBoardgame.png"> <h5> Optical tweezers to manipulate single cells </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/H_device_first.jpg"> <h5> Artificial selection of fast reproducing yeast with <strong>microfluidics</strong> </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/telescope2.jpeg"> <h5> Amateur telescope making </h5></div>
  <div class="grid-item"> <h5> Bio-imaging software for low cost sickle cell diagnostics </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/featureMatch.png"><h5> Feature matching across images </h5></div>
  <div class="grid-item"><img src="http://pinardemetci.github.io/images/otter.jpeg"><h5> Otter: Newborn warmer compatible with phototherapy </div>
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