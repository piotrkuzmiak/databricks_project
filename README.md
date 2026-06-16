# Project Overview

This repository is organized as follows:

```text
./
├── databricks_sample_package/
│   ├── __init__.py
│   └── udfs/
│       ├── __init__.py
│       └── functions.py
├── notebooks/
│   ├── AWS interactions.ipynb
│   ├── Optimizations.ipynb
│   ├── pandas_udf.ipynb
│   ├── Parsing_invoices.ipynb
│   └── pipeline_notebook.ipynb
├── tests/
│   ├── __init__.py
│   └── test_functions.py
├── pyproject.toml
└── README.md
```

## Folder Descriptions

- **databricks_sample_package/**: Python package code for shared utilities and UDF implementations.
- **notebooks/**: Jupyter/Databricks notebooks for analysis, experimentation, and prototyping.
- **tests/**: Unit tests for validating package behavior and functions.
- **pyproject.toml**: Package and dependency configuration for the Python project.
- **README.md**: This file. Provides an overview and structure of the repository.

---

Feel free to update this structure as the project evolves.