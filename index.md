### Posts
{% for post in site.posts %}
  <div class="row">
    <div class="col-md-12">
      <dt><a href="{{ post.url }}">{{ post.title }}</a></dt>
      <dd>{{ post.excerpt }}</dd>
    </div>
  </div>
{% endfor %}
