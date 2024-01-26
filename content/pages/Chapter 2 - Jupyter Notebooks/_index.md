---
title: Chapter 2 - Jupyter Notebooks
bookCollapseSection: true
weight: 200
---

You can convert Jupyter notebooks to markdown using the following command:

```bash
jupyter nbconvert --to markdown --output-dir=content/pages/Chapter\ 2\ -\ Jupyter\ Notebooks/ content/pages/Chapter\ 2\ -\ Jupyter\ Notebooks/*.ipynb
```

Make sure nbconvert is installed:

```bash
pip install nbconvert
```