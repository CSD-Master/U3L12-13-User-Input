---
layout: tabbed-assignment
---

# Resources

{% if site.data.assignment.slides %}
* [Presentation Slides][slides]
{% endif %}
{% if site.data.assignment.template %}
* View the [submission template][template] - make a [copy of the submission template][copy-template]
{% endif %}
* [Lesson1][]
{% if site.data.assignment.lesson2 %}
* [Lesson2][]
{% endif %}

<!-- Don't edit links here, change them in _data/assignment.yml instead. -->

{% if site.data.assignment.lesson1  %}[lesson1]:  <{{site.data.assignment.lesson1}}>  {% endif %}
{% if site.data.assignment.lesson2  %}[lesson2]:  <{{site.data.assignment.lesson2}}>  {% endif %}
{% if site.data.assignment.slides   %}[slides]:   <{{site.data.assignment.slides}}>   {% endif %}
{% if site.data.assignment.template %}[template]: <{{site.data.assignment.template}}> {% endif %}
{% if site.data.assignment.template %}[copy-template]: <{{site.data.assignment.template}}/copy> {% endif %}
