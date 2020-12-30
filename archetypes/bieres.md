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

TODO : intro

<!--more-->

# Dégustation

- TODO
- TODO


# Étiquette

{{< figure src="{{ .Name | lower }}-etiquette.png" alt="L'étiquette {{ .Title }}" width="700rem" link=""{{ .Name | lower }}-etiquette.png"">}}

**[Licence](link-to-wikipedia "tooltip")** : TODO

# Anecdotes

TODO
