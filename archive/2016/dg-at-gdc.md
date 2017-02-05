---
layout: page
title: DG at GDC!
permalink: /dg-at-gdc/
---

# Announcing the Different Games GDC Ambassadors program!

{:.centered}
![alt text](/images/dg-at-gdc-1.png "Image of Different Games Conference 2014")

<div class="ambassadors-text">
  <p>This year our collective is honored to have been chosen to take part in the 2016 GDC Scholars Program alongside some of our favorite community based games organizations from around the world. 25 members of the collective and broader Different Games community have been offered the opportunity to represent the organization as Different Games Ambassadors to GDC. </p>
  <p>Ranging from students and emerging creatives to respected academics and established designers we are thrilled to welcome our 2016 Different Games Ambassadors to GDC!</p>
</div>

<div class="ambassdors-header">
  <h2>2016 Different Games Ambassadors to GDC</h2>
</div>

<div class="ambassadors">
  {% assign ambassadors = site.ambassadors %}
  {% for ambassador in ambassadors %}
  <div class="ambassador row">
    {% if ambassador.image %}
    <img src="{{ ambassador.image }}" alt="{{ ambassador.name }}" class="col-xs-12 col-md-3"></img>
    {% endif %}
    <div class="col-xs-12 col-md-9">
      <h3>{{ ambassador.name }} 
        {% if ambassador.twitter-id %}
          <a href="https://twitter.com/{{ambassador.twitter-id}}">@{{ ambassador.twitter-id }}</a> 
        {% endif %}
        {% if ambassador.website %}
          <a href="{{ambassador.website}}">website</a>
        {% endif %}
        </h3>
      <p>{{ ambassador.bio }}</p>
    </div>
  </div>
  {% endfor %}
</div>

If you’d like to join Different Games in continuing to build a more vibrant, diverse and inclusive games community for us all, please consider becoming a sponsor.