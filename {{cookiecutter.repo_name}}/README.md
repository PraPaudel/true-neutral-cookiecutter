# {{ cookiecutter.project_name }}

## Description

{{ cookiecutter.description }}

## Setup

If you haven't already, create a Conda environment for your new project:

```
cd {{ cookiecutter.repo_name }}
conda create --name {{ cookiecutter.repo_name }} python=3.11
conda activate {{ cookiecutter.repo_name }}
pip install -e .
```

