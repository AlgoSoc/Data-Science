# Virtual Environment Guide

A **virtual environment** helps you manage Python packages for each project separately, so you don’t run into conflicts between projects.  

This guide will show you how to create, activate, and use a virtual environment in Python.

## Why Use a Virtual Environment ?

- Keeps project dependencies **isolated**.
- Avoids **version conflicts** between projects.
- Makes it easier to **share projects** with others.
- Allows for **reproducibility** of your work.

## Create a Virtual Environment

Open your terminal in your project folder and run:

```bash
python3 -m venv venv
```

## Activate the Virtual Environment

- macOS/Linux:

```bash
source venv/bin/activate
```

- Windows (Command Prompt):

```bash
venv\Scripts\activate
```

- Windows (PowerShell):

```bash
venv\Scripts\Activate.ps1
```

> When activated, your terminal prompt will show (venv).

## Install Packages

Once activated, install packages using `pip`:
> Packages installed here are only available in this environment.

## Deactivate the Virtual Environment

```bash
deactivate
```

> Returns you to your system’s default Python environment.

## Optional: Share Dependencies

To let others recreate your environment:

```bash
pip freeze > requirements.txt
```

Others can then install the same packages with:

```bash
pip install -r requirements.txt
```

## Tips

- Always activate your venv before working on a project.
- Keep a `requirements.txt` file updated.

## Additional Resources

For more in-depth learning about Python virtual environments, check out these resources:

- [W3Schools: Python Virtualenv](https://www.w3schools.com/python/python_virtualenv.asp)  
- [Python Official Tutorial: venv](https://docs.python.org/3/tutorial/venv.html)  
- [Python Standard Library: venv](https://docs.python.org/3/library/venv.html)  
- [Dataquest: Complete Guide to Python Virtual Environments](https://www.dataquest.io/blog/a-complete-guide-to-python-virtual-environments/)
