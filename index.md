---
layout: page
css:
  - /assets/css/index.css
---


<p align="center">
  <img width="300" src="https://raw.githubusercontent.com/rli012/rli012.github.io/master/assets/img/wordcloud.png">
</p>
  
## Recent Publications

<p align="center">
  <img width="800" src="https://raw.githubusercontent.com/rli012/rli012.github.io/master/assets/img/publications.png">
</p>

## Software

<div id="clients-out" class="page-section cut1">
  <div id="clients">
    <div id="client-logos">
      {% for client in site.data.software %}
        <a class="client-img" href="{{ client.url }}" title="{{ client.name }}">
          <img alt="{{ client.name }}" src="assets/img/logos/{{ client.img }}" />
        </a>
      {% endfor %}
    </div>
  </div>
</div>
