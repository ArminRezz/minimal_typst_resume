# Minimal Typst Resume

This repository contains a super minimal Typst-based resume setup.

## Files

- **`main.pdf`** – The compiled PDF version of the resume.  
- **`main.typ`** – The main Typst file outlining your resume structure.  
- **`resume.typ`** – The styling/CSS-like file that controls the resume’s appearance.  
- **`refs.bib`** – Bibliography file for your publication references.

## Usage

In **LazyVim (Neovim)**, I use the `typst-preview.nvim` plugin to see live updates side by side.  

To generate a new PDF:

```bash
typst compile main.typ

[main.pdf](https://github.com/user-attachments/files/23565810/main.pdf)
