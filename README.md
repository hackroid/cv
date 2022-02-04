# Hackroid's CV >_<

## About

Hackroid's latest version resume made with XeLaTeX. It uses [**zachscrivena/simple-resume-cv**](https://github.com/zachscrivena/simple-resume-cv) template.

> This version may revised based on the original design.
>
> Both the original version and my revised version are open sourced in public domain.

中文版本请移至[main-cn](https://github.com/hackroid/cv)分支 (Todo)

## Usage

**VSCode plugin is highly recommended**, otherwise:

The main XeLaTeX source file is `CV.tex`; the compiled document is `CV.pdf`.

Instructions for compiling the document (TeX &rarr;(XeLaTeX)&rarr; PDF):

- **Method 1:** Use `latexmk` for fully automated document generation:
	- `latexmk -xelatex "CV.tex"`
	(add the `-pvc` switch to automatically recompile on changes)
- **Method 2:** Use `XeLaTeX` directly:
	- `xelatex "CV.tex"`
	(run multiple times to resolve cross-references if needed)

## Checklist

The following checklist literally evaluates an eligible engineer's cv. Those criteria are collected from my professor, my friends, and the web. Maybe it's not suitable for you entirely, so just pick whatever you like.

- [x] Dense and clear
- [x] In ONLY **ONE** page
- [x] Concise, no nonsense
- [x] No typo and badly mixed case
- [x] LinkedIn and GitHub profile
- [x] Period and city of experience
- [x] No photo
- [x] PDF
- [ ] Red flag clarification / 有明显的 red flag 且没有在 cover letter 里解释，比如有 career gap，没有相关工作经验
- [ ] No unrelavent skills like Office
- [ ] Skills supported by specific work/project experience
- [ ] Company name appears in cover letter, customized
- [ ] Matched Introducer
- [ ] ...

## License

This is free and unencumbered software released into the public domain.
For more information, please see the file `LICENSE` or refer to <http://unlicense.org>.

Copyrighted fonts are not subjected to this License.
