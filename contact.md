---
layout: singlePage
title: "Fun"
---

# Contact


<html>
<style>
.grid-container {
  display: grid;
  grid-template-columns: 350px 350px
  grid-column-gap: 20px;
  border: 0px;
}

.grid-item {
  border: 0px
}

.calendar {
    text-align: center;
}
.column {
  float: left;
  width: 50%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>

<div class="grid-container">
  <div class="grid-item"> <strong>E-mail: </strong> <a href="mailto:pinardemerci@gmail.com"> pinardemetci@gmail.com </a> or <a href="mailto:pinar_demetci@brown.edu"> pinar_demetci@brown.edu </a> <br>

  <strong>Calendar: </strong> 
  <div class="calendar">
  <iframe src="https://calendar.google.com/calendar/embed?height=500&wkst=1&bgcolor=%23ffffff&ctz=America%2FNew_York&src=cGluYXJfZGVtZXRjaUBicm93bi5lZHU&color=%233F51B5&mode=WEEK&showDate=1&showNav=1&showTitle=1&showPrint=0&showTabs=1&showCalendars=1&showTz=1" style="border:solid 1px #777" width="400" height="300" frameborder="0" scrolling="yes"></iframe>
</div> <br>

<strong>Office Address: </strong><br>
164 Angell Street. 3rd Floor. <br>
Center for Computational Molecular Biology<br>
Providence, Rhode Island<br>
</div>

<div class="row">
  <div class="column">
    <img src="http://pinardemetci.github.io/images/CCMB_out.jpeg" alt="CCMB Outside" style="width:100%">
  </div>
  <div class="column">
    <img src="http://pinardemetci.github.io/images/CCMB_in.jpeg" alt="CCMB Inside" style="width:100%">
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