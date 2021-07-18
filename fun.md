---
layout: singlePage
title: "Fun"
---

# Fun and Hobbies
As we all know, mentorship matters. In my spare time, one of the things I like to do is introduce our foster cats to the world of computational biology. Two of them decided that this is indeed the field for them!

Here, you can find Wheezy listen to my [labmate Jeremy](https://rsinghlab.org/) present the [WaddingtonOT](https://www.cell.com/cell/pdf/S0092-8674(19)30039-X.pdf) paper (left), and take (somewhat lukewarm) interest in coding (right):

![One:Wheezy](images/wheezyLearning.jpeg){:height="36px"}
<img src="images/wheezyLearning.jpeg" alt="Two:Wheezy" width="36"/>
[<img src="images/wheezyLearning.jpeg" width="36"/>](images/wheezyLearning.jpeg)



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