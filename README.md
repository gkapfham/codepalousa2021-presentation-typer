# CodepaLOUsa 2021 Presentation

![](../../workflows/build/badge.svg) ![](../../workflows/release/badge.svg) [![Netlify Status](https://api.netlify.com/api/v1/badges/5dddd2ae-56ca-4047-a4f7-147059bb96f7/deploy-status)](https://app.netlify.com/sites/pyohio2021-presentation/deploys)

## Introduction

Slides created by [Gregory M. Kapfhammer](https://www.gregorykapfhammer.com/)
for a presentation given at [CodepaLOUsa
  2021](https://www.codepalousa.com/Default.aspx). The title of the
presentation is "Great On Their Own, Even Better Together: Application
Development with Python, Typer, and Poetry".

## Installation

To access the GitHub repository that contains the source code for these slides,
please follow these
[instructions](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository)
provided by [GitHub](https://github.com/). Once you have cloned the repository
to a directory on your computer, please change into it by typing the command `cd
pyohio2021-presentation` from the directory where you clone the repository.

## Commands

Now you are ready to view the presentation! To start the slide show:

- Type `npm install` to install the project's dependencies
- Type `npm run dev` to start a local development server
- Visit http://localhost:3030 to view the slides
- Visit http://localhost:3030/presenter to view the slides in presenter mode

The slide show also features other building and development options:

- Typing `npm run remote` will run an additional server supporting remote access
  to your laptop. Please see the diagnostic output for the correct address for
  the server.
- Typing `npm run build` will create a production version of the presentation in
  the form of static HTML
- Typing `npm run export` will create a PDF of the presentation.

Please note that, depending on your version of Playwright, the formatting of the
PDF-based presentation created by `npm run export` may vary slightly from the
version created by either the `npm run dev`, `npm run remote`, or `npm run
build` commands.

## Modifying or Adding Slides

You can edit the [slides.md](./slides.md) in a text editor. If you have a
development server running, then it will notice these changes and regenerate the
web sited and automatically reload your browser, allowing you to to see the
changes. You can learn more about Slidev by visiting its [web
site](https://sli.dev/).
