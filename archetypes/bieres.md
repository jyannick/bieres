---
title: "{{ replace .Name "-" " " | title }}"
pitch: "TODO"
featuredImg: "{{ .Name | lower }}.jpg"
thumbImg: "{{ .Name | lower }}-thumb.jpg"
date: {{ .Date }}
draft: true
brewMethod: "TODO: extraits de malt / tout grain"
recipe: "TODO"
recipeUrl: 
style: TODO
color: TODO
alcoolByVolume: 5
totalVolume: TODO L
description: >
  TODO Blablabla bla bla bla.
---

# Dégustation

- TODO
- TODO

# La référence

**[Licence](link-to-wikipedia "tooltip")** : TODO

# Étiquette

{{< img src="/bieres/img/{{ .Name | lower }}-etiquette.png" text="L'étiquette {{ .Name }}" >}}
TODO

# Anecdotes

TODO
