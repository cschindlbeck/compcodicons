---
layout: home
---

Compcodicons is a specialist icon font set for competitive coding/programming. It contains icons for websites and organistions related to competitive coding and programming that are often missing from mainstream repositories.

Available icons:

<div class="icon-container">
  <ul class="icon-list">
    {% for icon in site.data.icons %}
      <li title="{{ icon.name }}">
        <a href="{{ icon.url }}" class="icon-link" target="_blank" rel="noopener noreferrer">
          <i class="{{ icon.class }}"></i>
        </a>
        <div class="icon-name">{{ icon.name }}</div>
      </li>
    {% endfor %}
  </ul>
</div>

For an example of how to integrate this into your website, check out my [GitHub pages](https://cschindlbeck.github.io/).

<style>
  .icon-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
  }

  .icon-list {
    list-style-type: none;
    padding: 0;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  .icon-list li {
    font-size: 2em;
    text-align: center;
    margin: 10px;
  }

  .icon-name {
    display: block;
    margin-top: 5px;
    font-size: 0.5em;
  }
</style>
