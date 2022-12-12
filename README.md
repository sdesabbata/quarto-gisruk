
# Quarto GISRUK template

## Creating a new GISRUK extended abstract

To create a new article using this format:

```bash
quarto use template sdesabbata/quarto-gisruk
```

This will create a new directory with an example document that uses this format. 

## Using with an existing document

To add this format to an existing document:

```bash
quarto add sdesabbata/quarto-gisruk
```

Then, add the format to your document options:

```yaml
format:
  quarto-gisruk-pdf: default
```    

## Example

Here is the source code for a minimal sample document: [`template.qmd`](template.qmd). 

The minimal sample document was created using RStudio and includes an R code chunk which generates an L-function plot using `spatstat` as an example figure. If you do not have R and `spatstat` installed, you can remove the code chunk in lines 64 to 91 from the `template.qmd` example before rendering the document.

## Links

- An RMarkdown template: https://github.com/Robinlovelace/gisruk-rmd
- LaTeX example: http://leeds.gisruk.org/paper_templates/GISRUKPaperTemplate2015-Latex.zip
