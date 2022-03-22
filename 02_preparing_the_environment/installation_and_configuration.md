
**Installation and configuration** 

- Download and install Python [https://www.python.org/downloads/](https://www.python.org/downloads/)
- Download and install an IDE (VScode)
- Installation with pip (Python package manager) the libraries:
*`Pip install virtualenv`*
*`Python -m pip install --upgrade pip`*
*`Pip install virtualenvweapper-win`*


- Creating and accessing the project folder
- Creation of a virtual environment
*`Python -m venv ~~virtualenvironmentname~~`*
- Accessing the virtual environment:
*`.\env\Scripts\Activate.ps1`*

When the powershel has blocking:

*`Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSign`*

- Leaving the virtual environment
*`deactivate`*