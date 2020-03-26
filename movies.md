---
layout: movies
title: "Movie Recommendations"
---
{% for movie in site.movies %}
<article>
  <h2>{{movie.name}}</h2>
  <p>{{movie.rating}}</p>
    {{movie.content}}
  <p><a href="{{movie.source}}">Source</a></p>
</article>
{% endfor %}