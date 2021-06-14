<h2> Posts about Cloud Computing System</h2>

{% for category in site.categories %}
  <ul>
    {% for post in category[1] %}
        {% if category[0] ==  'cloud' %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endif %}
    {% endfor %}
  </ul>
{% endfor %}