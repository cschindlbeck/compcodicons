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

<style>
  .icon-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
  }

  .icon-list {
    list-style-type: none;
    padding: 0;
    margin: 0 auto; /* Center the list */
    display: flex;
    flex-wrap: wrap; /* Allow items to wrap to the next line */
    justify-content: center;
  }

  .icon-list li {
    font-size: 3em; /* Adjust the size of icons if needed */
    text-align: center; /* Center the content within list items */
    margin: 10px; /* Add some margin around each item */
  }

  .icon-list li .icon-name {
    display: block; /* Make the name block-level to center align */
    margin-top: 5px; /* Add some margin between icon and name */
    font-size: 0.5em; /* Adjust the font size if needed */
  }
</style>
