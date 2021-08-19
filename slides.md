---
theme: ./simple
class: text-center
highlighter: prism
colorSchema: light
download: true
preload: true
fonts:
  sans: IBM Plex Sans
  serif: IBM Plex
  mono: Fira Code
  italic: true
info: |
  ## CodepaLOUsa 2021
  CodepaLOUsa 2021
title: Great on their Own, Even Better Together
---

[//]: # (Slide Start {{{)

# Great on their Own, Even Better Together

## Application Development with
## Python, Typer, and Poetry

<div class="container my-5">
  &nbsp;
</div>

### Gregory M. Kapfhammer

### CodepaLOUsa 2021

[//]: # (Slide End }}})

---

[//]: # (Slide Start {{{)

# <em>Okay</em>, what is this about?

<style>
  h2 {
    font-size: 36px;
    @apply text-orange-600 mb-4;
  }
</style>

<br>

<div v-click>

## Key Questions

> What are the **benefits** and **challenges** associated with using the Python
> language, Typer, and Poetry for creating command-line
> applications?

</div>

<br>

<div v-click>

## Intended Audience

> An **adventuresome** technology enthusiast who wants to explore how both a
> new **paradigm** and software **tools** can improve their development skills!

</div>

<div v-click>

<div class="flex row">

<uim-rocket class="text-6xl ml-8 mt-5 text-blue-600" />

<div class="text-3xl font-bold mt-8 ml-4">
Let's create a command-line application in Python!
</div>

</div>

</div>

[//]: # (Slide End }}})

---

[//]: # (Slide Start {{{)

# Why focus on Python programming?

<style>
  h2 {
    font-size: 36px;
    @apply text-orange-600 mb-4;
  }
</style>

<br>

<div v-click>

## Prevalence of Python

> Python is consistently ranked as one of the **top programming languages**
> for web development, data science, machine learning, and general programming

</div>

<br>

<div v-click>

## Command-Line Interface

> Programmers who start using Python through Jupyter notebooks may need to
> create **tools** and **servers** that require a command-line interface

</div>

<div v-click>

<div class="flex row">

<mdi-help-box class="text-6xl ml-8 mt-4 text-blue-600" />

<div class="text-3xl font-bold mt-8 ml-4">
What is challenging about programming in Python?
</div>

</div>

</div>

[//]: # (Slide End }}})

---

[//]: # (Slide Start {{{)

<div class="flex row">

<mdi-package-variant class="text-8xl ml-9 mt-8 text-orange-600" />

<div class="text-6xl text-true-gray-600 font-bold mt-8 ml-4">
Creating virtual environments
</div>

<div class="text-6xl text-true-gray-600 font-bold mt-13 mr-15">
<ul>
<li> virtualenv </li>
<li> venv </li>
<li> pipenv </li>
</ul>
</div>

</div>

<v-clicks>

<div class="flex row">

<mdi-package-up class="text-8xl ml-9 mt-8 text-orange-600" />

<div class="text-6xl text-true-gray-600 font-bold mt-8 ml-4">
Publishing packages to PyPI
</div>

<div class="text-8xl text-true-gray-600 font-bold mt-15 mr-19">
<ul>
<li> twine </li>
<li> flit </li>
<li> setup.py </li>
</ul>
</div>

</div>

</v-clicks>

<v-clicks>

<div class="flex row">

<mdi-console class="text-8xl ml-9 mt-8 text-orange-600" />

<div class="text-6xl text-true-gray-600 font-bold mt-8 ml-4">
Making command-line interfaces
</div>

<div class="text-8xl text-true-gray-600 font-bold mt-14 mr-19">
<ul>
<li> argparse </li>
<li> fire </li>
<li> click </li>
</ul>
</div>

</div>

</v-clicks>

[//]: # (Slide End }}})

---

[//]: # (Slide Start {{{)

<div class="flex row">

<div class="text-7xl text-orange-600 font-bold mt-5 ml-4 mb-4">
How to easily create command-line tools using modern Python?
</div>

</div>

<div v-click>

<div class="flex row">

<uim-repeat class="text-6xl ml-8 mt-6 text-blue-600" />

<div class="text-5xl font-bold mt-8 ml-4">
Typer: <code>https://typer.tiangolo.com/</code>
</div>

</div>

</div>

<div v-click>

<div class="flex row">

<uim-layer-group class="text-6xl ml-8 mt-6 text-blue-600" />

<div class="text-5xl font-bold mt-8 ml-4">
Poetry: <code>https://python-poetry.org/</code>
</div>

</div>

</div>

[//]: # (Slide End }}})

---

[//]: # (Slide Start {{{)

<div class="ml-8 grid grid-cols-2 gap-19">
<div>

# Typer

<style>
  li {
  font-size: 22px;
  margin-bottom: 10px;
  }
</style>

- *Annotations* : assign types to functions accepting arguments
- *Productivity* : types aid in the creation of the interface
- *Checking* : confirm that inputs match expected types

</div>

<div v-click>

<div>

# Poetry

- *Environments* : manage dependencies in isolation
- *Package* : create a stand-alone executable application
- *Publish* : expedite and simplify the release of program to PyPI

</div>

</div>

</div>

<div v-click>

<div class="flex row">

<uim-scenery class="text-6xl ml-8 mt-5 text-blue-600" />

<div class="text-3xl font-bold mt-8 ml-4">
New way to manage application dependencies
</div>

</div>

</div>

<div v-click>

<div class="flex row">

<uim-grid class="text-6xl ml-8 mt-5 text-blue-600" />

<div class="text-3xl font-bold mt-8 ml-4">
Adjust to the challenge of adding type annotations
</div>

</div>

</div>

[//]: # (Slide End }}})

---

<v-clicks>

<div class="flex row">

<uim-repeat class="text-8xl ml-9 mt-8 text-orange-600" />

<div class="text-6xl text-true-gray-600 font-bold mt-8 ml-4">
Easy command-line interface with Typer
</div>

</div>

<div class="flex row">

<uim-layer-group class="text-8xl ml-9 mt-8 text-orange-600" />

<div class="text-6xl text-true-gray-600 font-bold mt-8 ml-4">
Manage, package, and release with Poetry
</div>

</div>

<div class="flex row">

<uim-github class="text-8xl ml-9 mt-8 text-blue-600" />

<div class="text-5xl text-true-gray-600 font-bold mt-15 ml-4">
AnalyzeActions/WorkKnow
</div>

</div>

</v-clicks>

<!--

In the remainder of this talk I'm going to use source code and type checker
output to tell you two stories!

- **Read the command-line interface comment**
- **Read the defect finding comments**

The experiences that I share in this talk took place in the context of building
an open-source program, called WorkKnow, that keeps you "in the know" about the
history of workflow builds on GitHub Actions. WorkKnow uses GitHub's REST API to
download the history of workflow executions. It then extracts, parses, and
summarizes the data and stores the most important results in CSV files.

**CUT IN SHORT VERSION**

I'm building and using WorkKnow because it helps me to gain insights into the
trends evident in both my GitHub action workflows and the workflows of popular
projects that leverage GitHub Actions.

If you would like to try out WorkKnow you can find it in the AnalyzeActions
organization on GitHub. Even though the tool is in a very early stage of
development, I hope that you will try it out, raise issues, and add new
features.

Okay, let's dive into my experience with using type annotations to build this
tool!

-->

---

[//]: # (Slide Start {{{)

# Creating the Application with Poetry

<style>
  h2 {
    font-size: 36px;
    @apply text-orange-600 mb-4 font-mono;
  }
  ul {
    @apply text-7xl text-orange-600 mb-4;
  }
  li {
    font-size: 22px;
    margin-bottom: 10px;
  }
</style>

<br>

<div v-click>

## poetry new workknow

<div class="flex row">

<div class="border-2 rounded-2xl border-gray-700 bg-true-gray-300 p-5 mr-15">

<pre>
├── coverage.xml
├── poetry.lock
├── pyproject.toml
├── README.md
├── tests
│  ├── __init__.py
│  ├── test_constants.py
│  └── test_request.py
└── workknow
   ├── __init__.py
   ├── analyze.py
   ├── concatenate.py
   ├── configure.py
   ├── constants.py
   ├── display.py
   ├── environment.py
   ├── files.py
   ├── main.py
</pre>

</div>

<v-click>

<div class="flex row mt-18 text-2xl">

- Create a simple directory structure
- Default support for testing with Pytest
- Store separate modules in directory
- The main file stores command-line interface
- The pyproject.toml file stores dependencies
- The poetry.lock file pins dependencies

</div>

</v-click>

</div>

</div>

[//]: # (Slide End }}})

---

# Command-Line Interface with Typer

<div class="ml-2 my-2">

```python {all|1-4|5|6-8|all}
import typer
cli = typer.Typer()
@cli.command()
def download(
    repo_urls: List[str],
    repos_csv_file: Path = typer.Option(None),
    results_dir: Path = typer.Option(None),
    env_file: Path = typer.Option(None),
):
```

</div>

<v-click>

<div class="flex row">

<uim-github class="text-7xl ml-0 mt-0 text-blue-600" />

<div class="text-4xl font-medium mt-6 ml-4">
See <code>AnalyzeActions/WorkKnow</code> for details!
</div>

</div>

</v-click>

<!--

Let's create a command-line interface for WorkKnow.

If you have not yet tried the Typer package for the construction of command-line
interfaces in Python then you should right away! It is awesome!

Now we can review this source code segment to better understand how Typer works
and how it uses type annotations.

<br>

**Review each highlighted line of source code.**

- The first four lines of the function import typer and designate that the
download will be one of the program's main commands

- Download's first parameter is a list of GitHub repository URLs with builds to
analyze

- The next three parameters are pathlib Path objects to files and directories
that WorkKnow needs to collect inputs and save output

WorkKnow's command-line interface also accepts other arguments. Checkout its
GitHub repository for more details!

-->

---

## Command-Line Interface

<style>
  h2 {
    font-size: 42px;
    @apply text-orange-600 mb-4;
  }
  li {
    font-size: 28px;
    margin-top: 4px;
    margin-bottom: 9px;
  }
</style>

<div class="border-2 rounded-2xl border-gray-700 bg-true-gray-300 p-5">

<pre>
Usage: workknow download [OPTIONS] REPO_URLS...
  Download the GitHub Action workflow history of repositories.
Arguments:
  REPO_URLS...  [required]
Options:
  --repos-csv-file PATH
  --results-dir PATH
  --env-file PATH
  --peek / --no-peek              [default: False]
  --save / --no-save              [default: False]
  --debug-level [DEBUG|INFO|WARNING|ERROR|CRITICAL]
                                  [default: ERROR]
  --help                          Show this message and exit.
</pre>

</div>

<div v-click>

<div class="flex row">

<uim-rocket class="text-9xl ml-5 mt-5 text-blue-600" />

<div class="text-3xl font-bold mt-7 ml-4">

- Using type annotations, Typer can:
  - automatically generate all menus
  - perform error checking on all arguments
  - convert all arguments to the correct type

</div>

</div>

</div>

---

# Type Annotations in Python

<style>
  h1 {
    @apply text-6xl -my-2 leading-20 font-bold text-dark-100 text-orange-600;
  }
  h2 {
    @apply text-4xl leading-20 font-bold text-dark-100;
  }
  code {
    font-size: 36px;
  }
</style>

## Terribly Intimidating or Tremendously Informative?

<v-clicks>

<div class="flex row">

<uim-exclamation-triangle class="text-7xl ml-0 mt-0 text-blue-600" />

<div class="text-4xl font-medium mt-6 ml-4">
Programmers define types
</div>

</div>

<div class="flex row">

<uim-layer-group class="text-7xl ml-0 mt-8 text-blue-600" />

<div class="text-4xl font-medium mt-12 ml-4">
Automatically create command-line
</div>

</div>

<div class="flex row">

<uim-layers-alt class="text-7xl ml-0 mt-8 text-blue-600" />

<div class="text-4xl font-medium mt-12 ml-4">
Type checkers automatically find bugs
</div>

</div>

</v-clicks>

<!--

So, what have I introduced in this talk?

First, I showed you how a programmer can define type annotations in their Python
program. Although these annotations take time to add and can make a program
appear more complex, they have a myriad of benefits!

For instance, when you use the Typer package it will automatically create a
robust and well-documented command line interface! Make sure that you search
for Typer and read its the exceptional documentation.

The talk also showed how typer checkers can automatically find bugs.

-->

---

# Type Annotations in Python

<style>
  h1 {
    @apply text-6xl -my-2 leading-20 font-bold text-dark-100 text-orange-600;
  }
  h2 {
    @apply text-4xl leading-20 font-bold text-dark-100;
  }
  code {
    font-size: 36px;
  }
</style>

## Yes, they are Tremendously Informative! Try them!

<v-clicks>

<div class="flex row">

<uim-github class="text-7xl ml-0 mt-0 text-blue-600" />

<div class="text-4xl font-medium mt-6 ml-4">
AnalyzeActions/WorkKnow
</div>

</div>

<div class="flex row">

<uim-comment-dots class="text-7xl ml-0 mt-8 text-blue-600" />

<div class="text-4xl font-medium mt-12 ml-4">
https://www.gregorykapfhammer.com/
</div>

</div>

<div class="flex row">

<uim-github class="text-7xl ml-0 mt-8 text-blue-600" />

<div class="text-4xl font-medium mt-12 ml-4">
gkapfham/pyohio2021-presentation
</div>

</div>

</v-clicks>

<!--

I'm hoping that you are now saying to yourself that, yes, type annotations in
Python are tremendously informative!

Whether or not you are now convinced of this fact, I hope that you will try them
soon. If you want see a Python program that is using type annotations, check out
WorkKnow's GitHub repository.

Once you have formed your own opinion about type annotations, I hope that you
will get in touch with me through my web site and leave a comment on YouTube.

Oh, one last thing! Are you interested in seeing the source code for my slides?
If so, please check the GitHub repository for their source code!

Okay, thanks for your attention! Now, get out there and write some Python code
with type annotations!

-->
