### Blogs

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <br>{{ page.date }}
    </li>
  {% endfor %}
</ul>

***
twitter:xxxx