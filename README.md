# Template Rzine

Modèle de mise en page [Quarto](https://quarto.org) pour les articles de la revue Rzine


## Créez un nouvel article

You can use this as a template to create an article for Rzine. To do this, use the following command:

```bash
quarto use template rzine-reviews/quarto-template
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation for existing document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto add template rzine-reviews/quarto-template
```

## Usage

To use the format, you can use the format names `rzine-html`. For example:

```bash
quarto render index.qmd --to rzine-html
quarto render index.qmd --to rzine-pdf
```

or in your document yaml

```yaml
format:
  rzine-html: default
  rzine-pdf: default
```

You can view a preview of the rendered HTML and PDF template at ....
