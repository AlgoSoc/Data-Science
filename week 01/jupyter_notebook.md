# Jupyter Notebook Guide

Jupyter Notebook is an interactive environment where you can write and run Python code, visualize data, and document your workflow all in one place. It’s widely used in Data Science for experiments, tutorials, and reporting.

## Why Use Jupyter Notebook?

- Interactive coding: run code cell by cell.
- Combine code, text (Markdown), and visualizations.
- Easy to share notebooks with colleagues or students.
- Great for prototyping and exploring data.

## Install Jupyter Notebook

Activate your [virtual environment](venv_guide.md) and install Jupyter with:

```bash
pip install notebook
```

## Launch Jupyter Notebook

Navigate to your project folder in the terminal, then run:

```bash
jupyter notebook
```

- This opens Jupyter in your default web browser.
- The interface shows your project files and allows you to create new notebooks.

## Notebook Basics

### Creating a New Notebook

1. Click **New → Python 3**.
2. A new notebook opens with an untitled name. Rename it by clicking on the title.

### Cells

- **Code cells**: write Python code and run with `Shift + Enter`.
- **Markdown cells**: write formatted text (headings, lists, links, etc.) for documentation.

### Toolbar

- Save: 💾
- Add cell: ➕
- Run cell: ▶️
- Restart kernel: 🔄 (resets your Python environment)

## Example: Hello World in a Notebook

1. Create a new code cell.
2. Type:

```python
print("Hello, Jupyter!")
```

3. Press `Shift + Enter` to execute.

You can also try simple calculations or plots here.

## Saving & Exporting Notebooks

- Save notebooks with `File → Save and Checkpoint`.
- Export as PDF, HTML, or Python script via `File → Download As`.

## Tips

- Restart the kernel if things stop working (`Kernel → Restart`).
- Use Markdown to document your steps makes notebooks easier to follow.
- Keep code cells short and organized.
- Always save your notebook regularly.

## Additional Resources

- [Jupyter Official Documentation](https://docs.jupyter.org/en/latest/)
- [DataCamp: Jupyter Notebook Tutorial](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
- [Real Python: Jupyter Notebook Tips](https://realpython.com/jupyter-notebook-introduction/)
