---
title: <% tp.file.title %>
date: <% tp.date.now("YYYY-MM-DD HH:mm:ss") %>
categories: [<% tp.file.folder(true).split("/").slice(-1)[0] %>]
tags: [读书笔记]
sticky: 0
---

# <% tp.file.title %>

> 书籍信息：[[<% tp.file.folder(true).split("/").slice(-1)[0] %>]]

<% tp.file.cursor() %>