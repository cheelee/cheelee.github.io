## Welcome to Chee Wai's Home for Public Technical Projects

### My Homepage

[Chee Wai's Home Page](http://cwleehome.blogspot.com/) is where one
can find more information about myself.

### Personal Github Projects

Apologies for not being able to get this table aligned for now.

| Project Page  | Description      |  Repo |
{% for repository in site.github.public_repositories %}
   {% if repository.has_pages %}
      {% if repository.name != "cheelee.github.io" %}
| [{{ repository.full_name }}]({{ repository.homepage }}/{{ repository.name }}) | {{ repository.description }} | [Link]({{ repository.html_url }}) |
      {% endif %}
   {% endif %}
{% endfor %}

### OpenWorm

Please also check out my volunteer work with the
[OpenWorm](https://github.com/openworm) organization:

- [Worm Movement Database](https://github.com/openworm/movement_cloud) 

