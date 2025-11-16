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

<img width="987" height="1278" alt="Screenshot 2025-11-15 at 11 42 17 PM" src="https://github.com/user-attachments/assets/6337aefa-b7fe-413a-ac40-9c7f9d71382c" />

