
# Science Journals

This is a Quarto template that assists you in creating a manuscript for *Science* Journals.
See [the *Science* website](https://www.science.org/content/page/preparing-manuscripts-using-latex) for more information on LaTeX submissions.

For final submission, you will need to make some manual edits to the TeX source, to inline the `.bbl` and and figure references.


## Creating a New Article

To create a new article using this format:

```bash
quarto use template CoryMcCartan/science
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add CoryMcCartan/science
```

Then, add the format to your document options:

```yaml
format:
  science-pdf: default
```    

## Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

