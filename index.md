# FlamiDev's blog

Mostly recipes and other fun stuff!

## Posts

{% for page in site.pages %}

{% assign ext = page.name | split:'.' | last %}

{% if ext == "md" and page.name != "index.md" %}

- [{{page.title}}]({{page.url}})

{% endif %}

{% endfor %}
