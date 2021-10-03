---
layout: page
---


<p align="center">
  <img width="300" src="https://raw.githubusercontent.com/rli012/rli012.github.io/master/img/worldcloud.png">
</p>
  
## Recent Publications

<p align="center">
  <img width="800" src="https://raw.githubusercontent.com/rli012/rli012.github.io/master/img/publications.png">
</p>


<div id="clients-out" class="page-section cut1">
  <div id="clients">
    <div class="section-title">Clients</div>
    <div id="clients-subtitle">Clients range from startups to universities to Fortune 500 companies</div>
    <div id="client-logos">
      {% for client in site.data.software %}
        <a class="client-img" href="{{ client.url }}" title="{{ client.name }}">
          <img alt="{{ client.name }}" src="img/logos/{{ client.img }}" />
        </a>
      {% endfor %}
    </div>
  </div>
</div>
