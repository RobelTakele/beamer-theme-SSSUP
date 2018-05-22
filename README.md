# beamer-theme-SSSUP

This repository provides a `LaTeX` theme implementation for the `beamer` 'documentclass' adequately consistent with the **SSSUP** official graphical design.

## Usage

In order to use the **SSSUP** theme, the following files should be included within the same directory where the main `*.tex` file resides:
 * `beamercolorthemeSSSUP.sty`
 * `beamerinnerthemeSSSUP.sty`
 * `beamerouterthemeSSSUP.sty`
 * `beamerthemeSSSUP.sty`
 * `sssup_logo.pdf`
 * `watermark.pdf`
 
The **SSSUP** theme should be explicitly included in the *preamble* of the main `*.tex` file with the folliwing command:

```TeX
\usetheme{SSSUP}
```

You can compile the document with your favourite `LaTeX` engine.
