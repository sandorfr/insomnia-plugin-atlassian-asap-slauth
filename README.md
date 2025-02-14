# Insomnia Plugin - Atlassian ASAP/SLAUTH Token Generator

![GitHub Workflow Status (event)](https://img.shields.io/github/workflow/status/usrivastava92/insomnia-plugin-atlassian-asap-slauth/Node.js%20CI)

This is a plugin for [Insomnia](https://insomnia.rest) that enables you to generate Atlassian SLAUTH or ASAP tokens.
Commands are executed using `child_process`.`exec`. ie., equivalent to `/bin/sh` `<cmd-specified>`

## Installation

Go to _Insomnia > Preferences > Plugins_, type in `insomnia-plugin-atlassian-asap-slauth` and click Install Plugin.

## Usage
Insert function either in headers or body either by typing `ctrl + space` or start type `{{`

- Choose your token type
- Fill mandatory or conditional mandatory fields depending on your token type

See screenshot below
![Screenshot](https://github.com/usrivastava92/insomnia-plugin-atlassian-asap-slauth/blob/master/example.png)
