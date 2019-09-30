.PHONY: lint

## runs juypter in a pipenv environment
jupyter:
	pipenv run jupyter lab


## installs jupyter lab extensions
jupyter-setup:
	pipenv run jupyter labextension install @jupyterlab/plotly-extension 


## Lint using flake8
lint:
	flake8 src

