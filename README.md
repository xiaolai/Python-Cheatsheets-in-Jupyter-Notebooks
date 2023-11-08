# README

Most of the content in this "tutorial" was adapted from wilfredinni's python-cheatsheet ([GitHub repo](https://github.com/wilfredinni/python-cheatsheet)), which has been transformed from `.html` format into an interactive `.ipynb` format for seamless execution in [Jupyter Notebook](https://jupyter.org/) or [JupyterLab Desktop](https://github.com/jupyterlab/jupyterlab-desktop).

## Table of Content

* [README.ipynb](README.ipynb)
* [cheatsheet.01.basics.ipynb](cheatsheet.01.basics.ipynb)
* [cheatsheet.02.Built-in.Functions.ipynb](cheatsheet.02.Built-in.Functions.ipynb)
* [cheatsheet.03.Control.Flow.ipynb](cheatsheet.03.Control.Flow.ipynb)
* [cheatsheet.04.Functions.ipynb](cheatsheet.04.Functions.ipynb)
* [cheatsheet.05.Lists.and.Tuples.ipynb](cheatsheet.05.Lists.and.Tuples.ipynb)
* [cheatsheet.06.Dictionaries.ipynb](cheatsheet.06.Dictionaries.ipynb)
* [cheatsheet.07.Sets.ipynb](cheatsheet.07.Sets.ipynb)
* [cheatsheet.08.Comprehensions.ipynb](cheatsheet.08.Comprehensions.ipynb)
* [cheatsheet.09.Manipulating.Strings.ipynb](cheatsheet.09.Manipulating.Strings.ipynb)
* [cheatsheet.10.String.Formatting.ipynb](cheatsheet.10.String.Formatting.ipynb)
* [cheatsheet.11.Regular.Expressions.ipynb](cheatsheet.11.Regular.Expressions.ipynb)
* [cheatsheet.12.File.and.Directory.Paths.ipynb](cheatsheet.12.File.and.Directory.Paths.ipynb)
* [cheatsheet.13.Reading.and.Writing.Files.ipynb](cheatsheet.13.Reading.and.Writing.Files.ipynb)
* [cheatsheet.14.JSON.and.YAML.ipynb](cheatsheet.14.JSON.and.YAML.ipynb)
* [cheatsheet.15.Exception.Handling.ipynb](cheatsheet.15.Exception.Handling.ipynb)
* [cheatsheet.16.Debugging.ipynb](cheatsheet.16.Debugging.ipynb)
* [cheatsheet.17.Args.and.Kwargs.ipynb](cheatsheet.17.Args.and.Kwargs.ipynb)
* [cheatsheet.18.Context.Manager.ipynb](cheatsheet.18.Context.Manager.ipynb)
* [cheatsheet.19.OOP.Basics.ipynb](cheatsheet.19.OOP.Basics.ipynb)
* [cheatsheet.20.Dataclasses.ipynb](cheatsheet.20.Dataclasses.ipynb)
* [cheatsheet.21.setup.ipynb](cheatsheet.21.setup.ipynb)
* [cheatsheet.22.Main.top-level.script.ipynb](cheatsheet.22.Main.top-level.script.ipynb)
* [cheatsheet.23.Virtual.Environment.ipynb](cheatsheet.23.Virtual.Environment.ipynb)
* [standard.library.01.Copy.ipynb](standard.library.01.Copy.ipynb)
* [standard.library.02.Datetime.ipynb](standard.library.02.Datetime.ipynb)
* [standard.library.03.Itertools.ipynb](standard.library.03.Itertools.ipynb)
* [standard.library.04.Json.ipynb](standard.library.04.Json.ipynb)
* [standard.library.05.Os.ipynb](standard.library.05.Os.ipynb)
* [standard.library.06.Pathlib.ipynb](standard.library.06.Pathlib.ipynb)
* [standard.library.07.Random.ipynb](standard.library.07.Random.ipynb)
* [standard.library.08.Shelve.ipynb](standard.library.08.Shelve.ipynb)
* [standard.library.09.Zipfile.ipynb](standard.library.09.Zipfile.ipynb)


## What is programming?

At its core, programming is all about handling data. Think of programmers as data wranglers, using coding languages to shape and channel data, which are just representations of real-world things and concepts.

To make life easier, every programming language comes with several basic data types, such as numbers, strings, or binary values. Building on these, you've got more complex types like lists (or arrays), dictionaries, maps, and objects.

Imagine data stored in variables as labeled boxes. These labels help programmers keep track of what type of data is inside. As a program runs, it’s essentially moving and transforming these boxes of data through various statements and functions.

Data wrangling requires a structured approach, and that's where "flow control" comes into play. It's the programming equivalent of a traffic signal, directing how tasks flow in the code. Sometimes actions run one after another (that's sequence), sometimes they repeat (loops), and sometimes they only happen under certain conditions (conditionals).

In any programming language, a statement is just an instruction to do something with data. And when tasks get complex, they can be bundled into "functions" for efficiency and reuse throughout the code.

As a beginner, grasp these concepts, and you're off to a solid start. And yes, being able to explain your code in plain English is a superpower in its own right!

## What is Python?

Python is a programming language that is known for its simplicity, ease of use, and beginner-friendly nature. It is also widely popular in the field of artificial intelligence (AI).

## Setting up the Development Environment

To set up a development environment on your computer, you can follow these steps:

1. Install Homebrew by running the following command in your terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Install JupyterLab Desktop using Homebrew by running the following command in your terminal:

```bash
brew install --cask jupyterlab
```

3. Manually set up the JupyterLab command-line interface (CLI) by running the following commands in your terminal:

```bash
sudo chmod 755 /Applications/JupyterLab.app/Contents/Resources/app/jlab
sudo ln -s /Applications/JupyterLab.app/Contents/Resources/app/jlab /usr/local/bin/jlab
```

Once you have completed these steps, you can launch JupyterLab Desktop either by typing "Jupyter" in Spotlight and clicking on the JupyterLab Desktop icon, or by using the CLI command "jlab" in the terminal.

Now you are ready to start using JupyterLab for your Python development.

## Get this tutorial to local

1. Install `git` by running the following command in your terminal:

```bash
brew install git
```

2. Clone this repo:

``` bash
mkdir ~/github
cd ~/github
git clone ....
```

3. Launch JupyterLab-Desktop to view notebooks:

```bash
cd ~/github/...
jlab .
```
