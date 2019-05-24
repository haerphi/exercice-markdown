
# Syntaxe markdown

## Les listes

### Non ordonnées

On précède chaque items par une astérisque "`*`".

* Item 1
* Item 2
  * Item 2a
  * Item 2b
* Item 3

### Ordonées

Pour imbriquer des listes, on indente la seconde liste dans la première.  

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

### Les liste de taches.

On crée ces listes en les précédant de "`-[]`" pour des items non cochés et "`-[x]`" pour des items cochés.

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### Imbrication

On imbrique des listes en les précédant par une indentation propre à chaque liste.

* Item 1
* Item 2
  1. Item 1
  1. Item 2
  1. Item 3
    - [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
    - [x] list syntax required (any unordered or ordered list supported)
* Item 3  

## Images  

Syntaxe à utiliser afin d'ajouter une image:  

`![Alt](url)`  

Une autre manière d'ajouter une image est:  

`![Alt](/home/user/images/img.png)`  

## Titres :
<br>

Voici comment créer plusieurs titres :<br>


`# Titre`: équivaut à `<h1>` en html <br>
`## Titre`: équivaut à `<h2>` en html<br>
et ainsi de suite jusqu'à arriver au `<h6>` : `###### Titre`.
<br>

## Mise en forme :<br>


* Gras : ``**texte**``<br>
* Italique : ``*texte*``<br>
      ou      `_texte_`<br>
* Gras & italique : ``***texte***``<br>
* Souligné : `__texte__`<br>
* Italique & souligné : `__*texte*__`
* Gras & souligné : `__**texte**__`
* Italique, gras & souligné : `__***texte***__`

## Liens :
<br>

Il y a 2 façons de faire :
* Soit en écrivant directement le lien en ayant pour nom l'url. *Ex :* http://github.com
* Soit en donnant un nom au lien `[nom du lien]` qui, en cliquant dessus, vous dirigera vers l'url `(url)`;`[Github](http://github.com)`. *Ex :* [Github](http://github.com)

## Code
Pour écrire du code en Markdown avec une coloration syntaxique il faut le code entre avec le nom du langage. <br>
Exemple: <br>
Pour faire ce ci:
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
Il faut faire cela:

    ```javascript
        function fancyAlert(arg) {
            if(arg) {
                $.facebox({div:'#foo'})
            }
        }
    ```
