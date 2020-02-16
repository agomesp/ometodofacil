# EASYPEASY

Git repository for EASYPEASY, a hackbook adapting *Allen Carr's EasyWay to Stop Smoking* for porn addiction. [The website automatically compiles the LaTeX document.](https://pmohackbook.org) It uses subfiles, located in the tex directory to compile the document.

Using XeLaTeX, provided you have texlive installed, run:

```
latexmk -pdf easypeasy.tex
```

On Windows, download a tex editor such as [texworks](https://www.tug.org/texworks/) and compile it using XeLaTeX.

Versions are numbered using [semantic versioning](https://semver.com).
