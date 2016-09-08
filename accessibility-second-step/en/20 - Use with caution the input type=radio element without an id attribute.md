---
id:         20
priority:   Risk
topic:      HTML
selector:   input[type=radio]
status:     not started
---

# Use with caution the input type=radio element without an id attribute

## Purpose

Permettre l'association des champs de formulaire avec les étiquettes qui les décrivent.

## Technical solution

Ajouter un attribut `id` sur l'élément.

## Control method

Inspecter le code source pour vérifier la présence d'un attribut `id` sur l'élément `<input type="radio" />`.