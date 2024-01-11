
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
  gisruk-pdf: default
```    


## Example

Here is the source code for a minimal sample document: [`template.qmd`](template.qmd). 

The minimal sample document was created using RStudio and includes an R code chunk which generates an L-function plot using `spatstat` as an example figure. If you do not have R and `spatstat` installed, you can remove the code chunk in lines 64 to 91 from the `template.qmd` example before rendering the document.



## Links

See also:

- [An RMarkdown template by Robin Lovelace](https://github.com/Robinlovelace/gisruk-rmd)
- [The GISRUK LaTeX template](https://gisruk.org/wp-content/uploads/2022/12/GISRUKPaperTemplate2015-Latex.zip)
- [The GISRUK Microsoft Word template](https://gisruk.org/wp-content/uploads/2022/11/GISRUK2023_PaperTemplateSubmission.docx)
