<!--
Copyright (c) 2023 Ernst Strüngmann Institute (ESI) for Neuroscience
in Cooperation with Max Planck Society
SPDX-License-Identifier: CC-BY-NC-SA-1.0
-->

# ESI Slidedeck Template

Template for preparing ESI-branded slides in [Quarto](https://quarto.org/) using the [reveal.js](https://revealjs.com/) backend.

## Description

This repository contains an exemplary slide-deck built with Quarto (and reveal) using the ESI corporate design. If you want to create an ESI-themed presentation in Quarto, this repository is probably a good place to start.

## Installation

Please install Quarto from the ESI Software Center (Linux clients come with Quarto pre-installed). Optionally, you might want to install the Quarto extension for VS Code.

## Usage

If you're working in VS Code and have the Quarto extension installed, simply open the command
palette (`CTRL` + `SHIFT` + `p` by default on Windows/Linux, `CMD` + `SHIFT` + `p` on macOS)
and execute *Quarto: Render Project*.
Alternatively, you can open a terminal window, navigate to directory containing this README
and type

```shell
quarto preview --render all --no-browser
```

and click on the displayed link (something like `http://localhost:1234/`)

## Support

For general questions related to Quarto, please visit the (excellent) [online documentation](https://quarto.org/docs/presentations/).

If you have questions/suggestion for the ESI template, please use our
[GitLab Issue Tracker](http://git.esi.local/it/esi-slidedeck-template/-/issues)

## Contributing

If you want to extend this template, feel free to fork the GitLab repository,
commit your changes and open a
[merge request](http://git.esi.local/it/esi-slidedeck-template/-/merge_requests).

## Authors and acknowledgment

Initial version created by @fuertingers design by @kernbergerc.

## Project Status

This project is actively maintained and (sometimes) updated.
