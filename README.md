Typst Resume

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
```
<img width="987" height="1279" alt="Screenshot 2025-11-15 at 11 43 52 PM" src="https://github.com/user-attachments/assets/99ae9e11-bdc3-4239-953e-6b95fad7e76a" />

<details>
  <summary>📷 Screenshot of Resume</summary>

  ![Resume Screenshot](Screenshot-2025-11-15.png)

</details>
