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
  - Class
tags:
  - Pathfinder2e
  - Pathfinder
  - SecondEdition
summary: Guide for the <% tp.file.title %> class.
class: <% tp.file.title %>
---

# <% tp.file.title %> Guide

## Class Description

## Class Features

## Subclass(s)

## Attributes

## Ancestries

## Class Feats

## Skill Feats

## Archetypes

## Equipment

## Example Builds