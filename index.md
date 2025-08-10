---
layout: archive
title: Home
permalink: /
---

<!-- About Section -->
<div id="about">
I am Jingyi Mei, a PhD student in Theoretical Computer Science at Leiden University.  
My research focuses on formal verification and quantum computing.  

I am passionate about exploring the theoretical foundations of computation and applying formal methods to ensure correctness and reliability in emerging quantum technologies.

Feel free to reach out via email or connect with me on GitHub and LinkedIn.

</div>

<div id="publications">
  <h2>Publications</h2>

  {% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
  {% for item in sorted_pubs %}
    <h3>{{ item.title }}</h3>

    <p><strong>Authors:</strong> {{ item.authors | join: ", " }}<br/>
    <strong>Publication:</strong> {{ item.publication }}<br/>
    {% if item.date %}
    <strong>Year:</strong> {{ item.date | date: "%Y" }}<br/>
    {% endif %}
    {% if item.url %}
    <a href="{{ item.url }}">Link</a><br/>
    {% endif %}
    {% if item.doi %}
    <a href="https://doi.org/{{ item.doi }}">DOI</a><br/>
    {% endif %}
    {% if item.keywords %}
    <strong>Keywords:</strong> {{ item.keywords }}<br/>
    {% endif %}
    </p>

    <hr/>
  {% endfor %}
</div>




<div id="talks">
  <h2>Talks</h2>

  {% for item in site.talks %}
    <h3>{{ item.title }}</h3>
    <p>{{ item.content }}</p>
  {% endfor %}
</div>

