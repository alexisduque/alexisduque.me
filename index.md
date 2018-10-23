---
layout: page
---
<h2>About Me</h2>

Welcome to my webpage !

I am leading the IoT Security department and the R&D activities at [Rtone](http://www.rtone.fr).

I have a Master of Engineering degree in Telecommunications from INSA Lyon (2015) and a Ph.D. in Computer Science from the University of Lyon (2018) after a thesis on Visible Light Communications for the IoT.

My thesis was in collaboration between Rtone and the [CITI laboratory](http://www.citi-lab.fr) under the CIFRE fellowship, and was supervised by [Razvan Stanica](http://perso.citi.insa-lyon.fr/rstanica/), [Hervé Rivano](http://perso.citi.insa-lyon.fr/hrivano/) and Adrien Desportes (Rtone Chief Executive Officer).

I am actively involved in the [PACLIDO](https://paclido.fr) collaborative project on lightweight cryptographic protocols for the IoT, for which I am the technical lead for Rtone.

I regularly attend IT conferences and give talks about security in IoT.

You can follow me on twitter [@alexis0duque](https://twitter.com/{{ site.author.twitter }}) and have a look on my [Google scholar]({{ site.author.google_scholar }}) profile.


<h2>Last News</h2>
<div class="posts">
  {% for post in site.posts limit:2 %}
      <h3 class="post-title">
        <a href="{{ site.baseurl }}{{ post.url }}">
          {{ post.title }}
        </a>
      </h3>
      <span class="post-date" style="margin-bottom:0px" >{{ post.date | date_to_string }}</span>
      <div class="post-more">
          <a href="{{ site.baseurl }}{{ post.url }}">
            ...
          </a>
      </div>

    {% endfor %}
</div>
