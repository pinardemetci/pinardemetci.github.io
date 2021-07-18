---
layout: singlePage
title: "Updates"
---

# Updates
#### Upcoming
<table class="table table-hover">
<tr>
  <td class='col-md-3'>August 2021 </td>
  <td> Presenting "Gromov–Wasserstein Optimal Transport to Align Single-Cell Multi-Omics Data" at the  <a href="https://www.recomb2021.org/accepted-papers"> 25th Annual International Conference on Research in Computational Biology (RECOMB) </a>.</td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>December 2021</td>
  <td>Invited speaker at "Optimal Transport in Machine Learning" Workshop at 2021 Conference on Neural Information Processing Systems (NeurIPS).</td>
</tr>
</table>

#### Past
<table class="table table-hover">
<tr>
  <td class='col-md-3'>27 May 2021 </td>
  <td> I passed my qualifying exam, defended my dissertation proposal, and advanced to candidacy!</td>
</tr><tr>
</tr>
<tr>
  <td class='col-md-3'>02 March 2021</td>
  <td> My Ph.D. co-adviser, Sorin Istrail, Ph.D., has been named <a href="https://www.iscb.org/iscb-news-items/4626-2021-march02-iscb-congratulates-introduces-2021-class-fellows">an International Society for Computational Biology (ISCB) fellow </a> for his "foundational contributions to computational biology, including physical mapping, protein folding, sequencing the human genome, haplotype phasing and assembly, and regulatory genomics, as well as launching the RECOMB conference and Journal of Computational Biology".</td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>February 2021</td>
  <td> I established my thesis committee and held an exploratory meeting to discuss my Ph.D. dissertation proposal.</td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>18 December 2020</td>
  <td> SCOT project (paper: <a href="https://www.biorxiv.org/content/10.1101/2020.04.28.066787v2"> "Gromov-Wasserstein optimal transport to align single-cell multi-omics data"</a>) has been accepted at the  <a href="https://www.recomb2021.org/accepted-papers"> 25th Annual International Conference on Research in Computational Biology (RECOMB) </a> </td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>10 December 2020</td>
  <td> My collaborator and co-first author, Rebecca Santorella, presents our paper titled <a href="https://www.biorxiv.org/content/10.1101/2020.04.28.066787v2"> "Gromov-Wasserstein optimal transport to align single-cell multi-omics data"</a> at <a href="https://iccabs.engr.uconn.edu/index.html#"> Computational Advances for Single-Cell Omics Data Analysis (CASCODA) Workshop. </a> </td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>24 November 2020</td>
  <td> I presented our our paper <a href="https://www.biorxiv.org/content/10.1101/2020.04.28.066787v2"> "Gromov-Wasserstein optimal transport to align single-cell multi-omics data"</a> at the <a href="https://sites.google.com/cs.washington.edu/mlcb2020/"> 2020 Machine Learning in Computational Biology (MLCB) conference. You can find the talk <a href="https://youtu.be/BYanbnKpwok?t=11364"> here. </a> </td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>10 November 2020</td>
  <td> My collaborator Rebecca Santorella and I presented our work on applications of optimal transport theory to single-cell integrated analysis of multi-omics data with a poster at the <a href="https://www.ima.umn.edu/2020-2021.1/W11.9-13.20"> Workshop on Optimal Control, Optimal Transport, and Data Science </a> hosted by <a href="https://www.ima.umn.edu/"> University of Minnesota Institute for Mathematics and Its Applications (IMA).</a> </td>
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