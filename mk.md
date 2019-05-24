# Les listes

Une liste est un ensemble fini d'éléments énumérés de manière séquentielle (les uns après les autres) dans un ordre signifiant ou sans ordre précis. C'est une manière simple et pratique d'organiser la pensée, souvent sous une forme matérielle écrite ou informatique. Umberto Eco distingue les listes pratiques (à la fonction référentielle) des listes poétiques (à la fonction de vertige grisant). Selon lui, les énumérations exhubérantes ont commencé à la Renaissance et se prolongent de nos jours dans les bibliothèques, « réceptacles » de listes. 1

## Non ordonnées

Les listes non ordonnées sont définies par une puces devant chaque items.
En markdown, on précéde chaque items par un asterisque "`*`".


* Item 1
* Item 2
  * Item 2a
  * Item 2b
* Item 3

## Ordonées

Les listes ordonnées sont définies par un nombre devant chaque items lui assignant un ordre.
En markdown, on précéde chaque items par un "`1.`".
Pour imbriquer des listes, on idente la seconde liste dans la première.  

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

## Les liste de taches.

Les listes ordonnées sont définies par une case a coché devant chaque items lui assignant une tache effectuée ou non.
en markdown, on crée ces llistes en les precedent de "`-[]`" pour des items non cochés et "`-[x]`" pour des items cochés.

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## Imbrication

Il est tout a fait possible d'imbriqué les differents types de listes.
en markdown, on imbrique des listes en les precedent par une identation propre a chaque listes.

* Item 1
* Item 2
  1. Item 1
  1. Item 2
  1. Item 3
    - [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
    - [x] list syntax required (any unordered or ordered list supported)
* Item 3

## Les tables
Vous pouvez créer des tableaux en assemblant
  * une liste de mots et en les divisant avec des tirets.- (pour la première ligne),
  * puis en séparant chaque colonne par un tuyau |:

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
