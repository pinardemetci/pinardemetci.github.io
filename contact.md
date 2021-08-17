---
layout: singlePage
title: "Fun"
---

# Contact


<html>
<style>
.grid-container {
  display: grid;
  grid-template-columns: 500px 500px
  grid-column-gap: 20px;
  border: 0px;
}

.grid-item {
  border: 0px
}

</style>

<div class="grid-container">
  <div class="grid-item"> <strong>E-mail: </strong> <a href="mailto:pinardemerci@gmail.com"> pinardemetci@gmail.com </a> or <a href="mailto:pinar_demetci@brown.edu"> pinar_demetci@brown.edu </a> <br>
  <strong>Calendar: </strong> <a href="pinardemetci.github.io/calendar"> Free/busy calendar </a><br>
<strong>Office Address: </strong><br>
164 Angell Street. 3rd Floor. <br>
Center for Computational Molecular Biology<br>
Providence, Rhode Island<br>
</div>

  <div class="grid-item"> <img src="http://pinardemetci.github.io/images/CCMB_out.jpeg"> <br>
<img src="http://pinardemetci.github.io/images/CCMB_in.jpeg">
  </div>
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