---
title: <% tp.file.title %>
date: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
categories: [<% tp.file.folder(true).split("/").slice(-1)[0] %>]
tags: []
---

# <% tp.file.title %>

<% tp.file.cursor() %>