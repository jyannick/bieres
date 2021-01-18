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
description: >
  TODO Blablabla bla bla bla.
---

# Dégustation

- TODO
- TODO

# La référence

{{< img src="{{ .Name | lower }}-etiquette.png" text="L'étiquette {{ .Title }}" >}}

**[Licence](link-to-wikipedia "tooltip")** : TODO

# Anecdotes

TODO
