---
layout: page
title: Units
---

<% collections.units.resources.each do |unit| %>
  <article>
    <a href="<%= unit.relative_url %>"><h2><%= unit.data.name %></h2></a>

    <p><%= unit.data.description %></p>
  </article>
<% end %>
<ul>
