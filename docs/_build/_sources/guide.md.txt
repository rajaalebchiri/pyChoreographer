---
myst:
  substitutions:
    HPC: "*Hypermodern Python Cookiecutter*"
---

# User Guide

This is the user guide
for the [Hypermodern Python Cookiecutter],
a Python template based on the [Hypermodern Python] article series.

If you're in a hurry, check out the [quickstart guide](quickstart)
and the [tutorials](tutorials).

## Introduction

### About this project

The {{ HPC }} is a general-purpose template for Python libraries and applications,
released under the [MIT license]
and hosted on [GitHub][hypermodern python cookiecutter].

The main objective of this project template is to
enable current best practices
through modern Python tooling.
Our goals are to:

- focus on simplicity and minimalism,
- promote code quality through automation, and
- provide reliable and repeatable processes,

all the way from local testing to publishing releases.

Projects are created from the template using [Cookiecutter],
a project scaffolding tool built on top of the [Jinja] template engine.

The project template is centered around the following tools:

- [Poetry] for packaging and dependency management
- [Nox] for automation of checks and other development tasks
- [GitHub Actions] for continuous integration and delivery

(features)=

### Features

Here is a detailed list of features for this Python template:

```{eval-rst}
.. include:: ../README.md
   :parser: myst_parser.sphinx_
   :start-after: <!-- features-begin -->
   :end-before: <!-- features-end -->

```