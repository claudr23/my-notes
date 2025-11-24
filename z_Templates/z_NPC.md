---
title: <% tp.file.title %>
aliases:
species:
Town: <% tp.file.folder() %>
class:
friendly:
---
![[Pasted image 20251124144003.png|200]]

| <% tp.file.title %> | <% tp.frontmatter.aliases %>  |
| ------------------- | ----------------------------- |
| Species             | <% tp.frontmatter.species %>  |
| Class               | <% tp.frontmatter.class %>    |
| Town                | <% tp.file.folder() %>        |
| Friendly to party   | <% tp.frontmatter.friendly %> |


