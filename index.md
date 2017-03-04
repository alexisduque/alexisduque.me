---
layout: page
---
<h2>About Me</h2>

Welcome to my webpage !  

I am working towards my PhD thesis at the [CITI laboratory](http://www.citi-lab.fr) within the INRIA [Agora](https://www.inria.fr/en/teams/agora) team, in the framework of French CIFRE fellowships with [Rtone](http://www.rtone.fr).

My PhD is under the joint supervision of [Razvan Stanica](http://perso.citi.insa-lyon.fr/rstanica/) and Adrien Desportes,
Chief Executive Officer at [Rtone](http://www.rtone.fr).

My research subject focuses on Visible Light Communication (VLC) and aims to develop suitable MAC/Application layers for a Smart City environment. Use cases and industrial applications are many, such as indoor localization or infrastructure-to-device communication.

If you like my website, you can follow me on twitter [@alexis0duque](https://twitter.com/{{ site.author.twitter }}) and have a look on my [Google scholar]({{ site.author.google_scholar }}) profile.


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