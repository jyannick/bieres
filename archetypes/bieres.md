---
title: "{{ replace .Name "-" " " | title }}"
pitch: "TODO"
featuredImg: "{{ .Name | lower }}.jpg"
thumbImg: "{{ .Name | lower }}-thumb.jpg"
date: {{ .Date }}
draft: true
brewMethod: "extraits de malt" TODO "tout grain"
recipe: "TODO"
recipeUrl: 
style: TODO
color: TODO
alcoolByVolume: 5
description: >
  TODO Blablabla bla bla bla.
---

# Dégustation

- TODO
- TODO

# La référence

**[Licence](link-to-wikipedia "tooltip")** : TODO
# Étiquette

{{< img src="{{ .Name | lower }}-etiquette.png" text="L'étiquette {{ .Title }}" >}}
TODO

# Anecdotes

TODO
