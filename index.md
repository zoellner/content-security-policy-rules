# Content Security Policy Rules

Stop reverse-engineering CSP rules. content-security-policy-rules.org is a collection of up-to-date Content Security Policy (CSP) rules for all major cloud services like Google Analytics, Facebook, Sentry, etc.

<ul>
{% for page in site.pages %}
  {% if page.url contains ".html" %}
    <li><a href="{{ page.url }}">{{ page.title | replace: " Content Security Policy Rules", "" }}</a></li>
  {% endif %}
{% endfor %}
</ul>
