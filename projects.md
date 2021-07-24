---
layout: singlePage
title: "Projects"
permalink: /projects/
description: 
nav: true
---
# Projects
I've had the opportunity to work on a number of engineering, science, coding and modeling projects outside of my dissertation research. Here, you can browse a selection of them (clickable details coming soon):

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
  cursor: pointer;
  box-shadow: 10px 10px 10px #bbbbbb;
}

div.grid-item:hover>h5{
  color: #4582ec;
}


</style>

<div class="grid-container">
  <div class="grid-item"> <h5> Optical tweezers to manipulate single cells </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/H_device_first.jpg"> <h5> Artificial selection of fast reproducing yeast with <strong>microfluidics</strong> </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/daktari1.png"> <h5> Amateur telescope making </h5></div>
  <div class="grid-item"> <h5> Bio-imaging software for low cost sickle cell diagnostics </h5></div>  
  <div class="grid-item"><img src="http://pinardemetci.github.io/images/otter.jpeg"><h5> Otter: Newborn warmer compatible with phototherapy </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/pacman.png"><h5> PacManAI: Reinforcement learning algorithm that plays PacMan </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/featureMatch.png"><h5> Feature matching across images </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/3dreconstruct.png"><h5> Computational 3D scene reconstruction from 2D images </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/3dreconstruct.png"><h5>Material science: Failure analysis of Zambian cast pots</h5></div>
  <div class="grid-item"> <h5> Recurrent neural networks for French <--> English machine translation </h5></div>
  <div class="grid-item"> <h5> 3D scanner with Arduino </h5></div>
  <div class="grid-item"><h5> Line following robot with simple PID control </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/3dreconstruct.png"><h5>Material science: Failure analysis of Zambian cast pots</h5></div>
</div>
</html>
<!--  biomechanics, generative model, graph network molecules, MCM model, modsim??? -->

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