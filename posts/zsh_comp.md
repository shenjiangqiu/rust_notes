---
title: zsh_comp
layout: default.liquid
description: a tour to add zsh completion function
---

# introduction to add completion to zsh
1. add a path for your completion scriptes: `mkdir ~/.zfunc`
2. generate the file for command `your_command`: `your_command -g=zsh >> ~/.zfunc/_your_command`
3. restart your shell and try