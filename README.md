# Article Rzine - Template

Modèle de mise en page [Quarto](https://quarto.org) pour les articles de la revue Rzine : [**Prévisualiser**]()


## Créez un nouvel article

Vous pouvez cloner (ou télécharger) le dépôt pour récupérer le template Rzine.

Vous pouvez également utiliser la ligne de commande suivante :


```bash
quarto use template rzine-reviews/quarto-template
```

Cela installe l'extension et créé un répertoire contenant un fichier `index.qmd` (code source de l'article) et des fichiers et répertoires associés.


## Appliquer le template à un document Quarto existant

Depuis le repertoire contenant le fichier .qmd ciblé :

```bash
quarto add template rzine-reviews/quarto-template
```

## Compliation du document

```bash
quarto render index.qmd --to rzine-html
quarto render index.qmd --to rzine-pdf
```


