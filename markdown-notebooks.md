---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Principales tecnologías de backend que debe conocer

Aquí vamos a discutir una de las mejores tecnologías de backend que lideran el mercado. Cada tecnología del lado del servidor tiene sus principales características y limitaciones. Es fundamental decidir cuál es la adecuada según los requisitos de su proyecto. Aquí hay una descripción general:

## Lenguaje de programación	

JavaScript

Aplicaciones famosas

```
Netflix
Candy Crush
Facebook
```

Frameworks

```
Express.js
React
Vue
```

## Create a notebook with MyST Markdown

MyST Markdown notebooks are defined by two things:

1. YAML metadata that is needed to understand if / how it should convert text files to notebooks (including information about the kernel needed).
   See the YAML at the top of this page for example.
2. The presence of `{code-cell}` directives, which will be executed with your book.

That's all that is needed to get started!

## Quickly add YAML metadata for MyST Notebooks

If you have a markdown file and you'd like to quickly add YAML metadata to it, so that Jupyter Book will treat it as a MyST Markdown Notebook, run the following command:

```
jupyter-book myst init path/to/markdownfile.md
```
