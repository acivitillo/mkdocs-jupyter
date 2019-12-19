# mkdocs-jupyter: Use Jupyter Notebooks in mkdocs

![mkdocs-jupyter](https://raw.githubusercontent.com/danielfrg/mkdocs-jupyter/master/screenshot.png)

- Add Jupyter Notebooks directly to the mkdocs navigation
- Feel and look the regular Jupyter Notebook style inside mkdocs pages
- Support for mkdocs TOC

## Usage

```
pip install mkdocs-jupyter
```

In your `mkdocs.yml`:

```
nav:
- Notebook: notebook.ipynb

plugins:
  - mkdocs-jupyter
```
