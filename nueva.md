---
layout: page

title: Categories
category:  aaa
lamine: yamal


---

<ul>
  {% for alumno in site.data.alumnos %}
    {% if alumno.edad > 18 %}
    <li>
      {{ alumno.nombre  | upcase }} {{ alumno.apellido }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>