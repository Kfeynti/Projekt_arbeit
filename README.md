# Abschluss_Projektarbeit1

About the Diabetes Dataset
Context

Diabetes is among the most prevalent chronic diseases in the United States, impacting millions of Americans each year and exerting a significant financial burden on the economy. Diabetes is a serious chronic disease in which individuals lose the ability to effectively regulate levels of glucose in the blood, and can lead to reduced quality of life and life expectancy. After different foods are broken down into sugars during digestion, the sugars are then released into the bloodstream. This signals the pancreas to release insulin. Insulin helps enable cells within the body to use those sugars in the bloodstream for energy. Diabetes is generally characterized by either the body not making enough insulin or being unable to use the insulin that is made as effectively as needed.

Complications like heart disease, vision loss, lower-limb amputation, and kidney disease are associated with chronically high levels of sugar remaining in the bloodstream for those with diabetes. While there is no cure for diabetes, strategies like losing weight, eating healthily, being active, and receiving medical treatments can mitigate the harms of this disease in many patients. Early diagnosis can lead to lifestyle changes and more effective treatment, making predictive models for diabetes risk important tools for public and public health officials.

The scale of this problem is also important to recognize. The Centers for Disease Control and Prevention has indicated that as of 2018, 34.2 million Americans have diabetes and 88 million have prediabetes. Furthermore, the CDC estimates that 1 in 5 diabetics, and roughly 8 in 10 prediabetics are unaware of their risk. While there are different types of diabetes, type II diabetes is the most common form and its prevalence varies by age, education, income, location, race, and other social determinants of health. Much of the burden of the disease falls on those of lower socioeconomic status as well. Diabetes also places a massive burden on the economy, with diagnosed diabetes costs of roughly $327 billion dollars and total costs with undiagnosed diabetes and prediabetes approaching $400 billion dollars annually.
Content

The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. Each year, the survey collects responses from over 400,000 Americans on health-related risk behaviors, chronic health conditions, and the use of preventative services. It has been conducted every year since 1984. For this project, a csv of the dataset available on Kaggle for the year 2015 was used. This original dataset contains responses from 441,455 individuals and has 330 features. These features are either questions directly asked of participants, or calculated variables based on individual participant responses.

This dataset contains 1 file:


    diabetes _ binary _ health _ indicators _ BRFSS2015.csv is a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes. This dataset has 21 feature variables and is not balanced.

Explore some of the following research questions:

    Can survey questions from the BRFSS provide accurate predictions of whether an individual has diabetes?
    What risk factors are most predictive of diabetes risk?
    Can we use a subset of the risk factors to accurately predict whether an individual has diabetes?
    Can we create a short form of questions from the BRFSS using feature selection to accurately predict if someone might have diabetes or is at high risk of diabetes?









































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
