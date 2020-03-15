---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% for product in site.products %}
  {% include product.html %}
{% endfor %}
{% for dream in site.dreams %}
  {% include dream.html %}
{% endfor %}
