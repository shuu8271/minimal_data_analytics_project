# Minimal Data Analytics Cookicutter Template

<!--- These are examples. See https://shields.io for others or to customize this set of shields. You might want to include dependencies, project status and licence info here --->
![GitHub top language](https://img.shields.io/github/languages/top/shuu8271/minimal_data_analytics_project?style=plastic)

Minimal Data Analytics Cookicutter Template is used to create a structured project folders including necessary files to start.

The structure is inspired by [Data Science Production](https://github.com/FilippoBovo/production-data-science/tree/master/tutorial/a-setup)

## Prerequisites

Before you begin, ensure you have met the following requirements:
<!--- These are just example requirements. Add, duplicate or remove as required --->
* You have installed Python with version 3.6+
* You have installed cookiecutter package [Follow instruction here](https://cookiecutter.readthedocs.io/en/latest/installation.html)

## Project Structure
```
📁 project_name/
    📁 src/
        📄 __init__.py
        📄 project_name.py
    📁 data/
        📄 README.md
    📁 exploration/
        📄 README.md
    📄 README.md
    📄 requirement.txt
    📄 .gitignore
```
Here is a description of the structure above:

* The folder src/ is dedicated to the source code for use in this project.

* `src/__init__.py` is an empty file to initialise the project package as a module.

    > Note that `__init__.py` files do not have to be empty and can be used, for example, to initialise code for the package.

* `data/` is to save source data to use in exploratory analyses

* `exploration/` is to save all notebooks used for exploratory data analysis

* requirement.txt is to install all the project related packages.

* The Markdown file README.md should contain a description of the project.

* .gitignore is used to ignore files from local repository.


## Using this cookiecutter template

To start using this cookiecutter,  follow below:

Open command line tool any type below coomand
```
cookiecutter https://github.com/shuu8271/minimal_data_analytics_project.git
```

Add run commands and examples you think users will find useful. Provide an options reference for bonus points!

## Contributing to <project_name>
<!--- If your README is long or you have some specific process or steps you want contributors to follow, consider creating a separate CONTRIBUTING.md file--->
To contribute to Minimal Data Science Cookicutter Template, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## References

* [Readme template](https://github.com/scottydocs/README-template.md)
* [Minimal Data Science project setup](https://github.com/FilippoBovo/production-data-science/)
* [Cookiecutter Data Science Template](https://drivendata.github.io/cookiecutter-data-science/)


## Contact

If you want to contact me you can reach me at yhcchen@outlook.com


## Remarks

.gitignore in project folder should only contain ignore files/folders related to this project

Everyone should set up their own global .gitignore
[Reference](https://sebastiandedeyne.com/setting-up-a-global-gitignore-file/)
