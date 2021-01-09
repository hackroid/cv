# Hackroid's CV >_<

## About

Hackroid's latest version resume made with XeLaTeX. It uses [**zachscrivena/simple-resume-cv**](https://github.com/zachscrivena/simple-resume-cv) template.

> This version may revised based on the original design.
>
> Both the original version and my revised version are open sourced in public domain.

中文版本请移至[main-cn](https://github.com/hackroid/cv)分支 (Todo)

## Usage

The main XeLaTeX source file is `CV.tex`; the compiled document is `CV.pdf`.

Instructions for compiling the document (TeX &rarr;(XeLaTeX)&rarr; PDF):

- **Method 1:** Use `latexmk` for fully automated document generation:
	- `latexmk -xelatex "CV.tex"`
	(add the `-pvc` switch to automatically recompile on changes)

- **Method 2:** Use `XeLaTeX` directly:
	- `xelatex "CV.tex"`
	(run multiple times to resolve cross-references if needed)

## License

This is free and unencumbered software released into the public domain.
For more information, please see the file `LICENSE` or refer to <http://unlicense.org>.

Copyrighted fonts are not subjected to this License.
