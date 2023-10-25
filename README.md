# Slide Deck For Presenting neuro-conda

Presentation at a programming course held by the Brain Research Institute
at Bremen University.

## Setup

The slides were built with [Quarto](https://quarto.org/) version 1.2.313.
To make the Quarto VS Code extension (and Quarto's web server) pick up
the HTML build, render the project

```shell
quarto render
```

Alternatively, a preview can be generated using

```shell
quarto preview --render all --no-browser
```

or directly from the Quarto extension by opening the command palette
(`CTRL` + `SHIFT` + `p` by default on Windows/Linux, `CMD` + `SHIFT` + `p` on macOS)
and executing *Quarto: Render Project*. Then click on the displayed link
(something like `http://localhost:1234/`)
