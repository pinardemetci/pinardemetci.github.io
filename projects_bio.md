---
layout: singlePage
title: "Projects"
permalink: /projects/bio
description: 
nav: true
---
# Projects (Other than Computational Biology)
**Outside of my dissertation research**, I've had the opportunity to work on a number of engineering, science, programming and modeling projects. Here, you can browse a selection of them **(clickable details coming soon)**:

<html>
<style>
.grid-container {
  display: grid;
  grid-template-columns: 225px 225px 225px 225px;
  grid-template-rows: 250px 250px 250px 250px 250px 250px;
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


.button-container {
  display: grid;
  grid-template-columns: 100px 210px 225px 100px 175px;
  grid-column-gap: 5px;
  grid-row-gap: 5px;
}
.button{
  background: #4582ec;
  border-radius: 10px;
  color: white;
  text-align: center;
  border: 0px;
  box-shadow: 5px 5px 5px #cccccc;
}
div.button:hover{
  cursor: pointer;
  box-shadow: 10px 10px 10px #bbbbbb;
  background: white;
  color: #4582ec;
}
.selectedButton{
  background: white;
  border-radius: 10px;
  color: #4582ec;
  text-align: center;
  border: 0px;
  box-shadow: 5px 5px 5px #cccccc;
}


</style>

<div class="button-container">
  <div class="button"><h6>All</h6></div>
  <div class="button"><h6>Computing/Modeling & ML</h6></div><!-- Computing / ML / Modeling -->
  <div class="selectedButton"><h6>Engineering & Bioengineering</h6></div> <!-- Engineering / Bioengineering -->
  <div class="button"><h6>Biology</h6></div> <!-- Biology -->
  <div class="button"><h6>Arts & Miscellaneous</h6></div> <!-- Art & Miscellaneous -->
  <br>
</div>

<div class="grid-container">
  <div class="grid-item"> <h5> Optical tweezers for non-contact manipulation of single cells </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/H_device_first.jpg"> <h5> Artificial selection of fast reproducing yeast with <strong>microfluidics</strong> </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/telescope2.jpeg"> <h5> Amateur handmade mirror telescope </h5></div>
   <div class="grid-item"><img src="http://pinardemetci.github.io/images/daktari2.png"><h5> Imaging software for low cost sickle cell diagnostics </h5></div>  
   <div class="grid-item"><img src="http://pinardemetci.github.io/images/eyeHelper.png"><h5> EyeHelper: Assistive software for blind shopping and navigation</h5></div>  
     <div class="grid-item"><img src="http://pinardemetci.github.io/images/otter.jpeg"><h5> Otter: Newborn warmer compatible with phototherapy </h5></div>
  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/zambianPot.png"><h5>Failure analysis of Zambian cast pots</h5></div>
  <div class="grid-item"><img src="http://pinardemetci.github.io/images/biomechanics.png"><h5> Biomechanical analysis of ultralight and standard hiking backpacks</h5></div>
  <div class="grid-item"><img src="http://pinardemetci.github.io/images/3DScanner.png"><h5> 3D scanner with Arduino </h5></div>
  <div class="grid-item"><h5> Line following robot with PID control </h5></div>
</div>
</html>
<!-- helmet,  generative model,  modsim??? data science? DeBruijn graphs for genome assembly, RNA Hybridization, Sequence alignment,interactive programming,  prisoners code breaker MCMC -->

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