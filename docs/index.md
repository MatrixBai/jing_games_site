
# Welcome to JING GAMES
{% if posts %}
  {% for post in posts | sort(attribute='date.created', reverse=true) | slice(3) %}
    <article>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
      <p><small>Posted on {{ post.date.created }}</small></p>
    </article>
  {% endfor %}
{% else %}
  <p>No blog posts found.</p>
{% endif %}