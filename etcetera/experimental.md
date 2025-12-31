# Et cetera

This is the rest. Things I wanted to keep on this website but didn't really fit in other tabs. Here you can find some quotations I like, links to websites I like, et cetera.

## Quotations

I love quotations. I've collected the following ones over the last several years. They are ordered according to the author's last name, year, and title. For quotes by fictional characters, I order them by the name of the actor (for movies or TV) or author (for books).

{%- assign listofquotes = site.quotes | sort: 'sortkey' -%}
{%- for quote in listofquotes -%}
{%- unless quote.category contains "sttng" %}

{% include quote.html quote=quote %}<br>

{% endunless %}
{% endfor -%}

## Star Trek Quotations

I started watching <a href="https://www.imdb.com/title/tt0092455/" target="_blank"><em>Star Trek: The Next Generation</em></a> a while ago and I've been taking notes of way too many quotes to keep them alongside the other ones. All of the following come from ST:TNG and I organize them by season and episode, instead of following the alphabetical patterns of the previous section. 

{%- assign listofquotes = site.quotes | where_exp:"item","item.category contains 'sttng'" | sort: 'sortkey' -%}
{%- for quote in listofquotes %}

{% include quote.html quote=quote %}<br>

{% endfor -%}