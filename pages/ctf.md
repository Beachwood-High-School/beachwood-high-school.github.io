---
layout: default
permalink: /ctf
---

# CTFs we have participated in


   <ol>
      {% for item in site.data.ctf %}
      <li>
        {{ item.name }} - Rank {{ item.rank }} - Percentile {{ item.rank | times:100 | divided_by: item.total }}%
      </li>
      {% endfor %}
    </ol>
