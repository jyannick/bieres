---
title: "{{ replace .Name "-" " " | title }}"
pitch: "Une bière qu'elle est bonne !"
featuredImg: "{{ .Name | lower }}.jpg"
thumbImg: "{{ .Name | lower }}-thumb.jpg"
date: {{ .Date }}
draft: true
brewMethod: "extraits de malt"
recipe: "recette maison"
recipeUrl: 
style: 
color: 
alcoolByVolume: 5
---

