Titre de niveau 1 (style Setext)
================================

## Titre de niveau 2 (style atx)

### Titre de niveau 3 (style atx) ###

Il est possible d'utiliser une *emphase légère* ou une **emphase forte**. Continuons avec un retour à la ligne  
forcé. Voici maintenant du `code en ligne`. On peut également échapper des caractères, par exemple \`ceci n'est pas du code, car les accents graves sont échappés\`.

N'oublions pas que du <strong>code HTML</strong> peut être inséré directement dans un document Markdown.

Voici à présent une liste non ordonnée:

- Item de liste non ordonnée créé avec le symbole `-`
+ Item de liste non ordonnée créé avec le symbole `+`
* Item de liste non ordonnée créé avec le symbole `*`

Pour sa part, une liste ordonnée ressemble à ceci:

1. Item de liste ordonnée

2. Item de liste ordonnée contenant un bloc de code:

		<em>Code HTML</em> affiché
		<strong>sans être interprété</strong>.

3. Item de liste ordonnée continuant sur un autre paragraphe:

	Suite de l'item.

Un autre élément qui peut être utilisé est la citation:

> Voici une citation, un peu comme dans les **courriels**.
>> On peut également ajouter *plusieurs niveaux de citation*.

Ajoutons des lignes horizontales:

----------
** ** ** ** **
__  __  __  __  __

Les liens ont aussi leur syntaxe:

- Lien automatique: <https://github.com/jpfleury/gedit-markdown>

- Lien incorporé au texte: le logiciel [gedit-markdown](https://github.com/jpfleury/gedit-markdown "Attribut title optionnel") permet d'ajouter le support du langage Markdown dans l'éditeur de texte gedit.

- Lien par référence: le logiciel [gedit-markdown][1] permet entre autres d'utiliser la coloration syntaxique du Markdown dans gedit.

- Autre lien par référence: le logiciel [gedit-markdown] permet entre autres d'utiliser la coloration syntaxique du Markdown dans gedit.

Il ne faudrait pas oublier les images:

- Image incorporée au texte: le logo de Wikipédia est ![Wikipedia](http://upload.wikimedia.org/wikipedia/commons/5/5a/Wikipedia-logo-v2-fr.png)

- Image par référence: le logo de Wikipédia est ![Wikipedia][logo wikipedia]

Les liens par référence créés un peu plus haut peuvent être définis n'importe où dans le texte, par exemple ici:

[1]: https://github.com/jpfleury/gedit-markdown
[gedit-markdown]: https://github.com/jpfleury/gedit-markdown

Même chose en ce qui concerne l'image par référence:

[logo wikipedia]: http://upload.wikimedia.org/wikipedia/commons/5/5a/Wikipedia-logo-v2-fr.png "Attribut title optionnel"
