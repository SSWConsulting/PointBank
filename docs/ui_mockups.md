
{% include alert.html text="Add your feedback to the UI Mockups through GitHub issues (on the left)" %}

{% assign screen_designs = site.static_files | where: "screen_design", true %}
{% for mockup in screen_designs %}
  <div class="row">
    <div class="col">
      <h3>{{ mockup.name }}</h3>
      <a href="{{ site.github.repository_url }}{{ site.github_source_root }}{{ mockup.path | attr_encode }}">
        <img class="img-fluid" src="/PointBank/{{ mockup.path }}">
      </a>
    </div>
  </div>
{% endfor %}


<div class="row">
  <div class="col">
    <p>This is a nice view of all the <a href="{{ site.github.repository_url }}{{ site.github_source_root }}/assets/screen_designs">UI mockups in GitHub</a></p>
  </div>
</div>