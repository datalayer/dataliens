# Dataliens Docs

This folder contains content for the [Dataliens ReadTheDocs website](https://dataliens.readthedocs.io).

```bash
# Install and build the doc site.
git clone https://github.com/dataliens/dataliens && \
  cd dataliens && \
  pip install -e .[rtd] && \
  cd docs && \
  make html && \
  open build/html/index.html
```
