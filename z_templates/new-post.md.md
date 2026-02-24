<%*  
const title = await tp.system.prompt("Post Title");  
await tp.file.rename(  
tp.date.now("YYYY-MM-DD") + "-" +  
title.replace(/\s+/g, "-").toLowerCase()  
);  
%>
---
title: <% tp.file.title %>
date: <% tp.date.now("YYYY-MM-DD") %>
draft: true
categories: ["Post"]
summary: "Short summary goes here."
tags:

---

# <% tp.file.title %>

Write your post here.