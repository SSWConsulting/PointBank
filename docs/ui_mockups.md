---
mockups:
    - 00 Login.png
    - 01 Dashboard.png
    - 02 My tasks.png
    - 03 Reward list.png
    - 04 Admin - Task list.png
    - 05 Admin - Add reward.png
    - 06 Admin - Configure users and groups.png
---

{% for mockup in page.mockups %}
  <h2>{{mockup}}</h2>
  <img src="{{ site.github.repository_url }}/blob/master/Documentation/Screen%20Designs/{{ mockup | attr_encode }}?raw=true">
{% endfor %}