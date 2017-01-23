---
published: true
category: blog
layout: blog
title: "Input / Output"
description: "Reading and manipulating data."
step: 1
---


This post demonstrates how to read and manipulate data from an Excel spreadsheet.

## Start Jupyter

1. Start the Anaconda navigator and click on the icon to launch Jupyter (looks like this:
<img src="http://jupyter.org/assets/main-logo.svg" alt="Jupyter logo" class="inline-image"/>).
Jupyter is a web-based interface to Python that lets you preserve text, code, and images all in one
single document. A new tab will open in your web browser. 
<img style="float:right;padding:0 1rem 0 0" src="img/new-notebooks-python.png"/>

2. Navigate to the directory where you want to store the notebook, and then click New → Notebooks → Python
(like in the image; the menu is on the top right) to open a new notebook. I have multiple versions of Python
installed; that's why mine has multiple options.

3. Another new tab will open. It contains a blank Jupyter notebook. You can change the name of the document
at the top left. I renamed mine to `input_output`. It will be saved (with the file extension  `*.pynb`)
as `input_output.ipynb`.


## Quick intro to Jupyter notebooks

### How to execute code

There will be an input cell at the top to type in, like this:
<img style="width:80%" src="img/input-cell.png"/>

To run code in it, type something like `print('hello')`, and then
press (`⇧ Shift`) + (`↵ Enter`) with the cursor in the cell.
This also makes a new cell to type in.
It is OK to overwrite the original cell, but the result of all of the code that
has been already executed will persist until you either shutdown and restart
your notebook, or click on one of the Restart options in Kernel → Restart.
To leave notes to yourself, either write comments in the code (below)
or use Markdown for extended statements (next)

```python
# Like this.
# This line also contains is a comment.
print('Hello world')  # Comments can also be inline.
```

### How to add text

Or convert the cell to "Markdown", by changing the <img class="inline-image" src="img/select-code.png" />
in the top menu to <img class="inline-image" src="img/select-markdown.png" />.
Markdown uses text cues to control formatting— for example, \*\*double asterisks\*\* render as **bold**.
Here's a link to [Markdown formatting][markdown].

In the mean time, you can type this at the top of your notebook for posterity:

```markdown
## Reading Excel files

This notebook demonstrates how to read and manipulate data from
Excel using [Pandas](http://pandas.pydata.org/):

* Input / Output
* summaries
* plotting
```

Press (`⇧ Shift`) + (`↵ Enter`) to render the Markdown.


## Start coding

The rest of the the tutorial can be followed directly via the Jupyter notebook:

<iframe
  src="http://nbviewer.jupyter.org/github/tanyaschlusser/stats-via-python/blob/master/notebooks/input_output.ipynb"
  style="width:120%;height:80vh;margin-left:-15%;">
</iframe>



[markdown]: http://jupyter-notebook.readthedocs.io/en/latest/examples/Notebook/Working%20With%20Markdown%20Cells.html
