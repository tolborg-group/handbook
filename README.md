# Handbook

This repository contains the source files for the handbook website. The site uses 
Quarto with quarto markdown (`.qmd`). These are as the name suggests a Markdown with a number of 
extra Quarto features. 

## Installation 

In order to edit the handbook it is recommended to use a local preview, this is most easily done by first ensuring that pixi is installed, see

- [Pixi installation](https://pixi.prefix.dev/latest/installation/)

Pixi is a modern package management tool (comparable to Conda but better and faster). 
With Pixi installed the environment required to preview the handbook can be setup with 

```sh
pixi install
```

Otherwise the environment will also be automatically installed if any pixi command that needs it are run.

## Previewing 

To preview run 

```sh
pixi r preview
```

This opens a live preview in your default browser and refreshes whenever you save a relevant file. 

## Markdown & Quarto 

Markdown is a commonly used language for prose, used e.g. in Jupyter notebooks, for a few key points see 

- https://www.markdownguide.org/cheat-sheet/

Quarto adds a number of additional features ontop of regular Markdown, the official documentation is very good, see 

- https://quarto.org/docs/guide/