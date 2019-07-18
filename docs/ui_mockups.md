
{% include alert.html text="Add your feedback to the UI Mockups through GitHub issues (on the left)" %}

This is a nice view of all the UI mockups in GitHub

{% assign screen_designs = site.static_files | where: "screen_design", true %}
{% for mockup in screen_designs %}
  <h3>{{ mockup.name }}</h3>
  <a href="{{ site.github.repository_url }}{{ site.github_source_root }}{{ mockup.path | attr_encode }}">
    <img src="{{ mockup.path }}">
  </a>
{% endfor %}