---
layout: course
name: "Основная информация о виртуальных машинах"
volume:  16 часов, 4 модуля
annotation: annotation
description: description about course
price_rub: 7500
--- 

<% collections.group_units.resources.each do |group_unit| %>
  <article>
    <a href="<%= group_unit.relative_url %>"><h2><%= group_unit.data.name %></h2></a>

    <p><%= group_unit.data.description %></p>
  </article>
<% end %>
<ul> 
