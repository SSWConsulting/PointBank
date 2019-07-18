
# This is a nice view of all the images in GitHub
{% assign screen_designs = site.static_files | where: "screen_design", true %}
{% for mockup in screen_designs %}
  <h3>{{ mockup.name }}</h3>
  <a href="{{ site.github.repository_url }}/tree/master/docs{{ mockup.path | attr_encode }}">
    <img src="{{ mockup.path }}">
  </a>
{% endfor %}