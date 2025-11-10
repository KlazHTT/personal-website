---
layout: page
title: Reading
permalink: /reading
---

Here is a list of books I have read or re-read, arranged in reverse chronological order. Thankfully, I knew how to read before 2023, but I unfortunately did not diligently keep track until then.

The purpose of this list is to help jog my memory and to help decide on my future reads.

Any star (★) denotes a great experience.

Jump to a particular year:
<ul class="media-list">
  {% for item in site.data.reads %}
    <li class="media-list-item">
      <a href="#{{ item.year }}"><span class="media-list-date">{{ item.year }}</span> <span class="media-list-count">({{ item.reads.size }})</span></a>
    </li>
  {% endfor %}
</ul>

 <div class="media-log">
   {% for item in site.data.reads %}
  <div class="media-log-section">
    <div class="media-log-year" id="{{ item.year }}" >{{ item.year }}</div>
    <div class="media-log-listing">
      {% for book in item.reads %}
      <div class="media-log-item">
        <div class="media-log-item-left">
          <span class="media-log-title">{{ book.title }}</span>
          {% if book.highlight == 'Y' %}<span class="media-log-highlight">★</span>{% endif %}
          <span class="media-log-date">{{ book.published }}</span>
          {% if book.status == 'Abandoned' %}<span class="media-log-status-abandoned">Abandoned</span>{% endif %}
        </div>
        <div class="media-log-item-right">
          <span class="media-log-creator">{{ book.author }}</span>
        </div>
      </div>
      {% endfor %}
    </div>
  </div>
  {% endfor %}
</div>

That's it. That's the end.

Thanks for reading.
