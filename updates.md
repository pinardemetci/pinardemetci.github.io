---
layout: singlePage
title: "Updates"
---

# Updates
#### Upcoming
<table class="table table-hover">
<tr>
  <td class='col-md-3'>August 2021 </td>
  <td> Presenting "Gromov–Wasserstein Optimal Transport to Align Single-Cell Multi-Omics Data" at the 25th Annual International Conference on Research in Computational Biology (RECOMB).</td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>December 2021</td>
  <td>Invited speaker at "Optimal Transport in Machine Learning" Workshop at NeurIPS.</td>
</tr>
</table>

#### Past
<table class="table table-hover">
<tr>
  <td class='col-md-3'>May 2021 </td>
  <td> I passed my qualifying exam, defended my thesis proposal, and advanced to candidacy!</td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>March 2021</td>
  <td><strong></td>
</tr>

</table>

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