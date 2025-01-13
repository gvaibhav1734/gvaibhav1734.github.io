---
date: '2025-01-13T12:49:42+05:30'
draft: false
title: 'Declarative setups with NixOS'
tags:
  - devoloper
  - operating-system
---

# But... Why?
Over the past 5 years I have had my fair share of changing laptops, setting up windows, sideloading Ubuntu, PopOS and more.
Naturally, the process is hard, effortful and forgetful! So I was looking for a more declarative way of setting up things 
and that's how I stumbled upon NixOS.

# How did I go about it?

The first encounter with NixOS... the configuration... the Nix language... the extensive documentation... I noped the F out of it!

However, thanks to tinkering with my laptop-screen connector and frying my motherboard (funny story btw),
I had to setup a new Laptop. The pain made me reconsider my choices.
This time around I found a beautiful book [nixos-and-flakes](https://nixos-and-flakes.thiscute.world/) which helped me in setting up my own
NixOS configs.

My typical setup is an Ubuntu with [Omakub](https://omakub.org/) and the follwing packages/applications/tools:
1. WezTerm - terminal emulator
2. LazyVim - neovim stuff
3. KeePass - password manager
4. Rclone - for syncing Google Drive
5. Zen Browswer - preferred browser
6. Chezmoi - for dotfiles

I replicated the same setup on NixOS and the configs are in this [repo](https://github.com/gvaibhav1734/nixos.git)!

