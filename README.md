# DAU-Analysis

## Analysis

This repository contains notebooks used especifically for analysing the DAU data, instructions are in [task.txt](task.txt). The notebook can be found inside [dau_analysis](./dau_analysis).

## Tests

By default Poetry creates a test folder, but for now there's no tests for this repository.

## Using poetry

1. Install [Poetry 1.1.14+](https://python-poetry.org/).
2. Install dependencies using `poetry install`.
3. Dependencies would be updated from `pyproject.toml`.
4. Create jupyter notebook kernel using `poetry run ipython kernel install --user --name dau-analysis`.
5. Activate environment using `poetry shell`.
6. Use jupyter notebook as usual selecting the correct kernel.
