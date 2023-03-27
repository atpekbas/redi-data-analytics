# Python Installation Guide

Before the first lecture, we would like you to set up your laptops by following this guide. This will install the tools that we will use in class and you will use in your homework and project. We will introduce you to what they are in class. If you have problems, try googling it, ask your team, or your colleagues; use your learning groups!

__Info__: Whenever you see a command in this guide, it is meant to put into a terminal window. The Terminal is an application in Windows, MacOS and Linux that runs code. In Windows, the app is called "Command Prompt". On MacOS and Linux it is "Terminal".

1. Download and install the latest Python version: https://www.python.org/downloads/
__Important__: Make sure to check all boxes, especially the __"Add Python to environment variables"__ checkbox. To check, if python was installed correctly, open up the Terminal/Command Prompt application on your laptop and type the following command. It should show you the installed python version.
    > python --version
2. Install pip by running the command:
    > python -m ensurepip --upgrade
3. Install Jupyter lab:
    > pip install jupyterlab
4. Install pandas and numpy:
    > pip install pandas numpy