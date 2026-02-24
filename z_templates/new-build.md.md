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
categories:
  - Build
tags:
  - Pathfinder2e
  - Pathfinder
  - SecondEdition
class: <% tp.prompt("Which class is this build for?") %>
summary: Build for <% tp.frontmatter.class %>.
---

# <% tp.file.title %>

## Concept
Brief description of the build.

## Stats
- Strength: 
- Dexterity: 
- Constitution: 
- Intelligence: 
- Wisdom: 
- Charisma: 

## Feats
- Class Feats:
- Skill Feats:
- Archetypes:

## Equipment

## Playstyle Notes

## Inspiration
Pop culture references or character flavor.