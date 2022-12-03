# nicholdav-info

My personal site.
A fork of [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/).
Adapted under MIT license
[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/mmistakes/minimal-mistakes/master/LICENSE)

Because I want to tweak the design, I am using a fork instead of installing as a gem.

If you like this site design, please consider supporting the original developer.
[![Tip Me via PayPal](https://img.shields.io/badge/PayPal-tip%20me-green.svg?logo=paypal)](https://www.paypal.me/mmistakes)
[![Donate to this project using Buy Me A Coffee](https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg)](https://www.buymeacoffee.com/mmistakes)

Minimal mistakes was also the source for [academicpages](https://github.com/academicpages/academicpages.github.io) by Stuart Geiger!

## Setup

1. set up a basic environment for working with `jekyll`
  - their quickstart is here: https://jekyllrb.com/docs/
  - I'm on PopOS, a Linux distribution similar to Ubuntu, and I use oh-my-zsh,
    so I followed these instructions: https://jekyllrb.com/docs/installation/ubuntu/
    except I changed `.bashrc` to `.zshrc`
2. follow directions for managing dependencies with `bundler`
  to install the `minimal-mistakes` template as a `gem`
  instead of forking their repo and modifying it
  + https://jekyllrb.com/tutorials/using-jekyll-with-bundler
* use `poetry` to set up an environment for `ghp-import`

## Usage

Building and publishing is done with the Makefile.
Run `make help` to see the commands.

## About the site design

Please see this rambling and poorly-edited blog post:
https://nicholdav.info/2022/03/16/how-to-use-jekyll-to-set-up-your-own-academic-website.html
