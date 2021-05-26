# Welcome to System Health Lab MkDocs Tutorial and Template
This is a tutorial and template based from [Mkdocs Frinze Template](https://github.com/frinzekt/mkdocs-frinze-template). This is a template that contains extensions that are very nice to have when you just want a standard documentation for anything!

For full documentation visit:

- [mkdocs.org](https://www.mkdocs.org) for the generic MkDocs
- [PyMdown Extensions](https://facelessuser.github.io/pymdown-extensions/) for the different extensions that are installed
- [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) for the customisation of the web server documentation.

## Why documentation?
Part of the success of every project is its maintainability, and that means that ability to pass on the knowledge and technical details to the people that will carry on the work.

## What is Markdown and what is Mkdocs?
Markdown is a simplistic markup language that is used to write documentations with a file that ends with `.md`. The greatest thing about markdown is its simplicity, this allows it to be rendered in many formats - `.docx`, `.pdf`, `.tex`, and with the case of Mkdocs, to render websites. Mkdocs is simply a renderer for markdown that generates files essential for websites (HTML, CSS, JS). These files allows the possiblity of deploying markdown documents into your own websites (in servers or external providers such as github pages).

There are a lot of places to learn how to write markdown, and due to its simplistic design, it is relatively easy to learn. Below the summary of a [guide](https://guides.github.com/features/mastering-markdown/#syntax) made by Github.

???+ note "Alternative"
    There are a lot of alternatives with MkDocs in the realms of markdown-based documentation such as [gitbook](https://www.gitbook.com/), [confluence](https://www.atlassian.com/software/confluence), [github wiki](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis), and [docusaurus](https://docusaurus.io/).

    In the side of other ways for documentation:

        - Onenote
        - Word Documents in OneDrive/Google Drive

## What do I hope to achieve with this tutorial and template?
This tutorial and template has 2 main purpose:

1. Make the documentation setup easier and accessible for everyone (template)
2. Teach Markdown (tutorial)

## How easy is this to deploy?

1.  Clone This [Repo](https://github.com/uwasystemhealth/shl-mkdocs-tutorial-and-template) or press the big green button "Use this template"
   1. Follow the [installation](#installation)
2. Delete the markdown files here and replace it with your own
3. Change a couple of things in the `mkdocs.yml` file (there are comments around it to make it easier)
4. Modify the `nav` in the `mkdocs.yml` file or delete it (Mkdocs will sort you documentation files to display)
5. Deploy somewhere ! (easiest way is with Github Pages see [here](#commands))


??? note "Branch Name"
    When you press "Use This template", the new repository will have "template" in its name. Change that in the Github >> Settings >> Branches >> Default Branch >> "Click the pencil icon".
## Installation
Install this preferably in your global environment because this is just a code generator and so.
```
pip install -r requirements.txt
```

???+ note "Prerequisite"
    You need to make sure that you have Python installed to be able to use `pip`. Here is the download [link](https://www.python.org/downloads/).
## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server. Very helpful when you want to take a look at the docs before deploying.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.
* `mkdocs gh-deploy` - Deploy in github pages

## Project layout
```
    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
```

## Extending this template

This template is made to be simple such that it gives you a brief overview of how you would be writing your documentation with a few configuration. This is the type of documentation that you just build on top of.

If in the scenario that you feel that I missed that is essential to be in the template, please feel free to give this repository a pull request. However, if you feel that you would like to extend this template much more, I would highly recommend to visit the original [Mkdocs Material Documentation](https://squidfunk.github.io/mkdocs-material/customization/).


## About this tutorial

There are 4 main portion of this tutorial, which are ordered sequentially:

1. Overview and Installation of Mkdocs (the current documentation you are looking at)
2. Writing Markdown
3. Flavoured Markdown
4. Deployment and Automated Deployment