# Faire

C'est un livre. Pour faire. 

## Auteurs:

- Manuel Schmalstieg
- Sedat Adiyaman

## Résumé: 

Faire est un livre qui vous aidera à : 
- monter les paliers de la productivité personnelle sans tomber de l’échelle.
- transformer les idées immatérielles en succès matériel
- décapsuler vos problèmes qui paraissent insurmontables 
- convaincre et vendre vos idées tout en créant du sens pour ce que vous aimez faire.


Composé de six étapes, ce livre vous guide pas-à-pas à générer et implémenter des idées - tout en gardant la pêche pendants le développement de vos compétences. 

## Technique:

Ce livre est produit avec Pandoc, un outil logiciel permettant de produire des sorties PDF à partir de fichiers texte en syntaxe MarkDown.

Pandoc utilise Latex comme moteur de génération de PDF.

Ce qu'il faut installer:

- Version actuelle de [Pandoc](http://pandoc.org)
- [BasicTeX](http://www.tug.org/mactex/morepackages.html), une version OSX de Latex.

### Erreurs possibles : 


Font not found: the font "FontAwesome" cannot be found.

Il faut installer la fonte FontAwesome, en la téléchargeant ici: http://fontawesome.io/

* Dézipper le fichier Zip téléchargé.
* Dans le dossier Fontawesome, ouvrir le dossier "fonts".
* Double-cliquer le fichier FontAwesome.otf pour l'installer.

#### Erreurs latex:

LaTeX Error: File `flushend.sty' not found.

Installer l'extension Latex "sttools" abec la commande Terminal suivante:

```
sudo tlmgr install sttools
```

LaTeX Error: File `hyphenat.sty' not found.

Installer l'extension "hyphenat" avec la commande suivante:

```
sudo tlmgr install hyphenat
```