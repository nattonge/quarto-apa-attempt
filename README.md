# APA style-ish template (APA)

<!-- ALL THE BELOW SHOULD BE IN YOUR README -->

This is a Quarto template that assists you in creating a manuscript for APA journals. I have never made a Quarto template before! This is mainly for personal use and so troubleshooting is limited; however, others are free to use - just let me know if it was helpful @na_tonge.

## Creating a New Article

You can use this as a template to create an article for an APA journal. To do this, use the following command:

```bash
quarto use template nattonge/quarto-apa-attempt
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto install extension nattonge/quarto-apa-attempt
```

## Usage

To use the format, you can use the format names `apa-attempt-pdf` and `apa-attempt-html`. For example:

```bash
quarto render article.qmd --to quarto-apa-attempt-pdf
```

or in your document yaml

```yaml
format:
  pdf: default
  apa-attempt-pdf:
    keep-tex: true    
```

## Format Options

This format does not have specific format option. Include documentation of such option otherwise. See <https://github.com/quarto-journals/elsevier#format-options> for an example.
