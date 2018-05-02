---
layout: page
title: DG @ GDC 2018
permalink: /dg-at-gdc/
---

# The 2018 Different Games @ GDC Ambassadors Program

The Different Games Collective is honored to announce that we have been chosen to participate in **the 2018 Game Developers Conference (GDC) Scholars Program.** We are delighted to share this opportunity with individuals, organizations and institutions that will help support Different Games Collective’s mission of fostering diversity and inclusivity in games and games culture.

## About the Program

The DG @ GDC 2018 Ambassadors Program includes passes to GDC, including talks and workshops, as well as one year of access to the GDC Vault. Ambassadors will have the opportunity to network with other members of the 2018 program, are invited to join us for a special event on the afternoon of Sunday, March 18th at the offices of Patreon.

***

## Our 2018 Ambassadors

<div class="ambassadors">
  {% assign ambassadors = site.ambassadors %}
  {% for ambassador in ambassadors %}
  <div class="ambassador row">
    {% if ambassador.image %}
    <img src="{{ ambassador.image }}" alt="{{ ambassador.name }}" class="col-xs-12 col-md-3"></img>
    {% endif %}
    <div class="col-xs-12">
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

***

If you have any questions, please feel free to email us at differentgamescollective@gmail.com
