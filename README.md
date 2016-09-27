# MkDocs Tutorial

## Purpose

A quick and easy little playground of files to use for experimenting with the [MkDocs](http://www.mkdocs.org/) static site generator.

## Context

This project represents a facetious static site documenting the use of Calculators. It demonstrates some YAML config and varied markdown files, along with a multi-layered directory of documents, to give you a little playground to try out MkDocs.

## Extremely Quick "Quick-start"

Clone this repository somewhere sensible, then:

* Install [Chocolatey](https://chocolatey.org/install)
* Open an elevated (administrator) Cmd prompt or Powershell session, then:
    * Enter the command `choco install python`
    * Read and accept any relevant prompts with `Y`
    * Enter the command `choco install pip`
    * Read and accept any relevant prompts with `Y`
    * Enter the command `pip install mkdocs`
    * Read and accept any relevant prompts with `Y`
* Once all that is installed, in your command prompt:
    * Navigate to this repository's directory
    * Enter the command `mkdocs serve`
    * Navigate to [http://127.0.01:8000/](http://127.0.01:8000/) in your browser
    * You should be able to see the MkDocs-generated site using the files in this repository!
* If you wish to build the site locally rather than just run it, enter the command `mkdocs build`

(Quick-start information largely taken and reduced to the bones from the [MkDocs home page](http://www.mkdocs.org/)).