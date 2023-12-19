---
title: ""
permalink: /teaching/
author_profile: true
---

<h2>Teaching Assistant</h2>
<ul>
  <li>
    <b>EEL4837 Programming for Electrical Engineers II</b><br>
    University of Florida, Spring 2023
      <ul>
        <li>Topics: C++, data structure, algorithms</li>
        <li><a href="https://www.ece.ufl.edu/wp-content/uploads/syllabi/Spring2023/EEL4837_Prog_EE_2_Ruchkin_Spring_2023.pdf">Syllabus</a></li>
      </ul>
  </li>
</ul>



{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
