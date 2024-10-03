# workshop_pydantic

pyenv local 3.11.5

poetry init

poetry add mkdocs

mkdocs new .

poetry run mkdocs serve

poetry add mkdocs-mermaid2-plugin

poetry add mkdocs-material

poetry add 'mkdocstrings[python]'

poetry add taskipy

poetry add pytest

poetry add isort
