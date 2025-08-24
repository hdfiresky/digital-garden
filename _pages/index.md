---
layout: page
title: Home
id: home
permalink: /
---

# Welcome to My Digital Garden

This is a space where I cultivate my thoughts, learnings, and ideas in technology. It's a collection of interconnected notes, constantly growing and evolving.

Unlike a traditional blog, these notes are not chronological. They are organized by topic and linked together to form a web of knowledge. This approach, inspired by the Zettelkasten method, helps in discovering new connections and building a deeper understanding.

## How to Navigate

- Click on any `[[wikilink]]` within a note to jump to a related topic.
- Check the "Backlinks" section at the bottom of each note to see which other notes refer to it.

Feel free to explore!

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>