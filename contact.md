---
layout: singlePage
title: "Contact"
---

# Contact


<html>
<style>
.calendar {
    text-align: left;
}
.column1 {
  float: left;
  width: 65%;
  padding: 10px;
}
.column2 {
  float: left;
  width: 35%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
.img{
	border: 0;
}

ul {
    display: inline;
    padding: 0;
}
li {
    display: inline;
}
</style>

<div class="row">
  <div class="column1">
<strong>E-mail: </strong> <a href="mailto:pinardemerci@gmail.com"> pinardemetci@gmail.com </a> or <a href="mailto:pinar_demetci@brown.edu"> pinar_demetci@brown.edu </a> <br>
<strong> Platforms & Profiles: </strong> <ul class="list-inline idxIcons" style='font-size: 1.5em; margin-top: 0.5em;'>
        <li>
          <a href="http://www.linkedin.com/in/pinardemetci" target="_blank">
            <i class="fa fa-fw fa-linkedin"></i></a>
        </li>
        <li>
          <a href="http://twitter.com/spinar_d" target="_blank">
            <i class="fa fa-fw fa-twitter"></i></a>
        </li>
      <li>
          <a href="https://scholar.google.com/citations?user=0Tzd6eAAAAAJ&hl=en" target="_blank">
          <i class="ai ai-google-scholar"></i></a>
        </li>
        <li>
          <a href="http://github.com/pinardemetci" target="_blank">
            <i class="fa fa-fw fa-github"></i></a>
        </li>
        </ul><br>
<strong>Calendar: </strong> If you want to schedule a call or a meeting, you can take a look at my calendar for available times:
  <div class="calendar">
  <iframe src="https://calendar.google.com/calendar/embed?height=500&wkst=1&bgcolor=%23ffffff&ctz=America%2FNew_York&src=cGluYXJfZGVtZXRjaUBicm93bi5lZHU&color=%233F51B5&mode=WEEK&showDate=1&showNav=1&showTitle=1&showPrint=0&showTabs=1&showCalendars=1&showTz=1" style="border:solid 1px #777" width="600" height="600" frameborder="0" scrolling="yes"></iframe>
</div> <br>
  </div>

  <div class="column2">
  	<strong>Office Address: </strong><br>
	164 Angell Street. 3rd Floor. <br>
	Center for Computational Molecular Biology<br>
	Providence, Rhode Island<br><br>
	<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d10622.493137944537!2d-71.40948743621925!3d41.82465499586538!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89e445234354f4cb%3A0x6131be74138e01c2!2s164%20Angell%20St%2C%20Providence%2C%20RI%2002906!5e0!3m2!1sen!2sus!4v1629242264241!5m2!1sen!2sus" width="325" height="244" style="border:0;" allowfullscreen="" loading="lazy"></iframe><br>
    <img src="http://pinardemetci.github.io/images/CCMB_out.jpeg" alt="CCMB Outside" style="width:100%"> <br>
    <img src="http://pinardemetci.github.io/images/CCMB_in.jpeg" alt="CCMB Inside" style="width:100%">
  </div>
</div>

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