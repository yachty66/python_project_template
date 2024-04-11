# python_project_template

This repository is a template for a Python project, designed to provide a standardized structure for Python development. It includes a basic package with a subpackage, a testing setup, documentation, and a main application file.

## Project Structure

The project has the following structure:

- `sample_package/`: The main package of the project. --> usually snake_case!
  - `subpackage/`: A subpackage contained within the main package. --> created when a module is > than one file
    - `__init__.py`: Initializes the subpackage as a Python package. --> necessary to allow import of the module
    - `subpackage_module.py`: Module inside the subpackage. --> modules also usually snake_case!
  - `__init__.py`: Initializes the sample_package as a Python package.
  - `helpers.py`: Helper functions used across the project.
  - `module.py`: A module with project-specific functions.
- `docs/`: Documentation files for the project.
  - `documentation.md`: The Markdown documentation for the project.
- `tests/`: Unit tests for the project.
  - `__init__.py`: Initializes the tests package.
  - `basic_test.py`: Basic unit tests for the project modules.
- `main.py`: The entry point of the application.
- `README.md`: This file, describing the project and how to use it.
- `requirements.txt`: A list of python package dependencies for the project.
- `LICENSE`: The license file for the project.

## How to use

Click "Use this template" and than give the repository you wanna create a name and youre good to go. 