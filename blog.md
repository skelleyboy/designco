---
layout: default
title: Blog
permalink: "/blog/"

---

<div id="main" role="main" class="container">
    <div class="posts">
      {% for post in site.posts %}

        <article class="post">

          <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

          <div class="entry">
            <a class="entryLink" href="{{ site.baseurl }}{{ post.url }}">{{ post.excerpt }}</a>
          </div>

          

        </article> 

      {% endfor %}
      
    </div>

</DIV>


