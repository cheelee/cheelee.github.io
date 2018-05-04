## Welcome to Chee Wai's Home for Public Technical Projects

### Personal Projects

| Project Page  | Description      |  Repo |
|---------------|:----------------:|------:|
{% for repository in site.github.public_repositories %}
   {% if repository.has_pages %}
      {% if repository.name != "cheelee.github.io" %}
| {{ repository.full_name }}]({{ repository.homepage }}/{{ repository.name }}) | {{ repository.description }} | [Link]({{ repository.html_url }}) |
      {% endif %}
   {% endif %}
{% endfor %}

### OpenWorm

Please also check out my volunteer work with the
[OpenWorm](https://github.com/openworm) organization:

- [Worm Movement Database](https://github.com/openworm/movement_cloud) 

