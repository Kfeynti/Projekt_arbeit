# Abschluss_Projektarbeit1


Precondition: Windows users can follow the official microsoft tutorial to install python, git and vscode here:

    ​​https://docs.microsoft.com/en-us/windows/python/beginners
    german: https://docs.microsoft.com/de-de/windows/python/beginners

Visual Studio Code

This repository is optimized for Visual Studio Code which is a great code editor for many languages like Python and Javascript. The introduction videos explain how to work with VS Code. The Python tutorial provides an introduction about common topics like code editing, linting, debugging and testing in Python. There is also a section about Python virtual environments which you will need in development. There is also a Data Science section showing how to work with Jupyter Notebooks and common Machine Learning libraries.

The .vscode directory contains configurations for useful extensions like GitLens and Python. When opening the repository, VS Code will open a prompt to install the recommended extensions.
Development Setup

Open the integrated terminal and run the setup script for your OS (see below). This will install a Python virtual environment with all packages specified in requirements.txt.

Windows Users

    run the setup script .\setup.ps1
    activate the python environment: .\.venv\Scripts\Activate.ps1
    run example code: python src/hello.py
    install new dependency: pip install sklearn
    save current installed dependencies back to requirements.txt: pip freeze > requirements.txt
