---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.2'
      jupytext_version: 1.6.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---

# Jupyter notebooks


## The traditional coding environment

The traditional approach to writing programs comprises writing the actual program in source code files (normally plain text) and documenting the code either as text comments within the source code files or separately in a word processed document or a website. There is nothing inherently wrong with this approach, however there are drawbacks. First, documentation in source code files relies on users being able to access and read the source code. This may be difficult for non-programmers. Second, documenting the functionality of software outside of the source code requires programmers to take an additional step to write documentation separately, and also to keep the documentation in sync with the code as its functionality changes. Among natural scientists, this often means that the documentation simply never gets written, or that it does not keep up with changes in the software, which may mean the documentation has little value. Clearly, a solution that would combine documentation of the code with the code itself would be quite helpful! This is one of the key attributes of the Juptyer notebook, described below.


## Jupyter notebooks: Code and documentation combined

![_**Figure 1.8**. Features of a Jupyter notebook._](../img/jupyter-notebook.png)

_**Figure 1.8**. Features of a Jupyter notebook._

Jupyter notebooks are an application that combines source code with rich-text documentation, equations, images, and plots in the form of a single interactive document (Figure 1.8). The notebooks are divided into cells, where each cell contains part of the document intended for either source code or documentation. The most common cell types for use in Jupyter notebooks are "Code" cells and "Markdown" cells, which naturally are designed for source code and Markdown-formatted text (Figure 1.9). The code cells support several different programming languages, including Python, and the Markdown cells are for creating nicely formatted text using the Markdown language. An example of the Code and Markdown cells can be found in Figure 1.9. To interact with the notebooks, they must be hosted on a server either locally or remotely, and accessed via a web browser.

![_**Figure 1.9**. An example Jupyter notebook._](../img/jupyter-notebook-window.png)

_**Figure 1.9**. An example Jupyter notebook._

Combining source code and documentation into a single document is an excellent solution to the problem of having these two exist separately in the traditional way of programming, however there are other benefits to Jupyter notebooks as well. For example, data science workflows often use Jupyter notebooks to provide complete descriptions of how the author loads, processes, and otherwise interacts with data files or other data sources in their data analysis. In this way, Jupyter notebooks can be used to give step-by-step descriptions of a data processing workflow, including producing plots and other data visualizations that are saved within the notebook. By including references to scientific articles and sources in the notebook, you can basically have a self-contained, reproducible scientific document where anyone can easily see exactly how you've done your analysis (and redo it themselves if they like). In terms of open science, this is a huge benefit.