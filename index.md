# FlamiDev's blog

Mostly recipes and other fun stuff!

## Posts

{% for post in site.posts %}

- [{{post.title}} ({{post.date | date: "%-d %B %Y"}})]({{post.url}})

{% endfor %}
