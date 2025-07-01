# clipclean

Smarter clipboard cleaning for macOS.

## Why

macOS adds invisible junk to your clipboard — from smart quotes to odd spacing.  
This tool removes it, giving you clean, copy-ready text.

## Features

- Removes invisible formatting, control characters, emojis  
- Converts curly quotes to straight quotes  
- Optionally collapses spacing and removes empty lines  
- Use `--preserve` to keep layout

## Install

Clone this repo and create a shortcut:

```bash
alias clipclean="bash /your/path/to/clipclean.sh"