https://github.com/twbs/bootstrap/releases

Pegar um exemplo do bootstrap:

https://getbootstrap.com/docs/3.3/getting-started/

dashboard

index.html -> templates/base.html.twig

dashboard.css -> assets/css/dashboard.css

{% block title %}{% endblock %}
{% block stylesheets %}
{% endblock %}
<link rel="stylesheet" href="{{ asset('build/js/app.css') }}">

{% block body %}{% endblock %}

{% block javascripts %}

<script src="{{ asset('build/js/app.js') }}"></script>

{% block body %}



criar Criar 
temp.html.twig

    {% extends 'base.html.twig' %}

    {% block body%}
        {{ dump(temp) }}
    {% endblock %}

    {% if form if defined %}

        {{ form_start(form) }}
            {{ form_widget(form) }}
            <input type="submit" value="Create" />
        {{ form_end(form) }}
    {% endif %}

