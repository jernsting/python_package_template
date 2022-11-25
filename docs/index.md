[![Python application](https://github.com/jernsting/python_package_template/actions/workflows/lindandtest.yml/badge.svg)](https://github.com/jernsting/python_package_template/actions/workflows/lindandtest.yml)
[![Coverage Status](https://coveralls.io/repos/github/jernsting/python_package_template/badge.svg?branch=master)](https://coveralls.io/github/jernsting/python_package_template?branch=master)
![GitHub](https://img.shields.io/github/license/jernsting/python_package_template)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=jernsting_python_package_template&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=jernsting_python_package_template)# How to use this template
This repository is a quick start template for new photonai modules. To get started simply follow these steps:

1. Klick "Use this template" button
2. Fill in details for the new photonai module
3. Wait for the repository to be created
4. Wait for the Github Actions to run once
5. As soon as the "✅ Ready to clone and code." commit appears in your repository you are ready to start coding
6. (optional) Remove "rename_project.yml" workflow from .github/workflows
7. (optional) Remove "rename_project.sh" from .github
8. Remove this how to section from readme

## Included features

- Code testing and coverage calculation (if coveralls secret **COVERALLS_REPO_TOKEN** is set)
- Continous Integration for testing and documentation updates based on Github Actions.
- MkDocs-Material based documentation template
- Photonai compatible **init.py** with boilerplate code for registration of new module

##  Development workflow: Add new algorithms

In order to add a new Algorithm / Feature to your project you can follow the steps below. By providing unit tests, a documentation and an example you maximize code quality and usability of your module.  

- Develop your learning algorithm
- Test your algorithms in a respective test file in the `test` folder 
- Document algorithms in the `docs` folder by copying and adapting the provided .md file
- Provide an example on how to use your algorithms in an appropriately named file in the examples folder.
