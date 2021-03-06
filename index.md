---
layout: page
---

<h3><b>Research Collaboration Opportunity</b></h3>
If you are looking for an SME to contribute to your collaborative research project, **Rtone will be happy to help**!

Our research interests and expertises are IoT, Cybersecurity, Embedded Machine Learning, Software Defined Radio, Wireless Communications, LPWAN, etc.

Get more information in this [short presentation](https://speakerdeck.com/alexisduque/research-at-rtone).

<h2><b>About Me</b></h2>

Welcome to my webpage !

I am director of research and lead the security activities at [Rtone](http://www.rtone.fr).

I am also a Research Associate at the Univesity of Edinburgh in the [Mobile Intelligence Lab](https://mi.inf.ed.ac.uk/) lead by [Paul Patras](http://homepages.inf.ed.ac.uk/ppatras/). I'm involved in the development of [Net AI](https://netai.tech), a university spin-out that develops an AI software to drive efficient network slicing.

I have a Master of Engineering degree in Telecommunications from INSA Lyon (2015) and a Ph.D. in Computer Science from the University of Lyon (2018) after a thesis in computer science on Visible Light Communications for the IoT.

My thesis was in collaboration between Rtone and the [CITI laboratory](http://www.citi-lab.fr) under the CIFRE fellowship, and was supervised by [Razvan Stanica](http://perso.citi.insa-lyon.fr/rstanica/), [Hervé Rivano](http://perso.citi.insa-lyon.fr/hrivano/) and Adrien Desportes (Rtone Chief Executive Officer).

I am actively involved in the [PACLIDO](https://paclido.fr) collaborative project on lightweight cryptographic protocols for the IoT, for which I am the technical lead for Rtone.

I regularly attend IT conferences and give talks about our work on IoT.

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
