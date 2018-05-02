## Welcome to Chee Wai's Home for Public Technical Projects

### Personal Projects

{% for repository in site.github.public_repositories %}
   {% if repository.has_pages %}
  * [{{ repository.name }}]({{ repository.homepage }})
   {% endif %}
{% endfor %}

### OpenWorm

Check out my volunteer work with the [OpenWorm](https://github.com/openworm) project:

- [Worm Movement Database](https://github.com/openworm/movement_cloud) 

