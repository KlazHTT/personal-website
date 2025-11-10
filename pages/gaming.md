---
layout: page
title: Gaming
permalink: /gaming
---

Here is a list of games that I've played or re-played, arranged in reverse chronological order.

From childhood, I have tried my best to recall the titles that I've played during this golden era of console gaming. Unfortunately, it is like that some titles have been lost in memory. For the sake of my sanity, these games are listed by platform release then by game release date as there is no way for me to remember exactly what order I played these titles, especially as I had access to different consoles through friends and family members.

Any star (★) denotes a great experience.

Jump to a particular year:
<ul class="media-list">
  {% for item in site.data.games %}
    <li class="media-list-item">
      <a href="#{{ item.year }}"><span class="media-list-date">{{ item.year }}</span> <span class="media-list-count">({{ item.games.size }})</span></a>
    </li>
  {% endfor %}
</ul>

 <div class="media-log">
   {% for item in site.data.games %}
  <div class="media-log-section">
    <div class="media-log-year" id="{{ item.year }}">{{ item.year }}</div>
    <div class="media-log-listing">
      {% for game in item.games %}
      <div class="media-log-item">
        <div class="media-log-item-left">
          <span class="media-log-title">{{ game.title }}</span>
          {% if game.highlight == 'Y' %}<span class="media-log-highlight">★</span>{% endif %}
          <span class="media-log-date">{{ game.released }}</span>
          {% if game.status == 'Replay' %}<span class="media-log-status-revisited">Replay</span>{% endif %}
          {% if game.status == 'Abandoned' %}<span class="media-log-status-abandoned">Abandoned</span>{% endif %}
        </div>
        <div class="media-log-item-right">
          <span class="media-log-creator">{{ game.developer }}</span>
        </div>
      </div>
      {% endfor %}
    </div>
  </div>
  {% endfor %}
</div>

That's it. That's the end.

Thanks for exploring.
