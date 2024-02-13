# Dotfiles

This directory contains my commonly used dotfiles - including aliases, bash configuration and all that cli sugar.


### Install

```bash
git clone -n https://github.com/TurtleException/homelab.git ~/.dotfiles \
  && cd ~/.dotfiles \
  && git sparse-checkout init --cone \
  && git sparse-checkout set dotfiles \
  && git checkout \
  && ~/.dotfiles/install.sh
```
