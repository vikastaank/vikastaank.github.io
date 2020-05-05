## {{include.title}} ({{include.category}})

{{include.problem}}


{{include.solution}}


{% if include.gist %}
{% gist include.gist include.gistfile %}
{% endif %}


{% for image in include.images %}
{% include elements/figure.html image=image %}
{% endfor %}
