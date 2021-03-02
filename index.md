## hja22 Blog

I'm a first-year PhD student at the Interactive AI CDT in Bristol.

### Posts

{% for post in site.posts %}
  [{{ post.title }}]({{ post.url }})

  {{ post.excerpt }}
{% endfor %}
