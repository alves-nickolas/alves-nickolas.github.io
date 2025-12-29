# Et cetera

This is under construction!

## Quotations

{% assign listofquotes = site.quotes | sort: 'sortkey' %}
{% for quote in listofquotes %}
{% include quote.html quote=quote %}
{% endfor %}