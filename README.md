# TeX_Beamer_Template

This is an example of a beamer presentation with a citation made by an independent .bib file.

## Usage

In order to compile it:
1. Run BibTeX at least twice on your .Tex / .Bib files (They need to be in the same folder).
2. Run LaTeX on your main .Tex file.

## How to make references?

If you want to make references, you can use [Google scholar](https://scholar.google.com/). By searching the needed book/article, you can get a *Cite* link, which will provide to you with a *BibTeX* code that you can copy and paste onto the .Bib file.

## How to add more slides?

Just use the 
```latex
	\begin{frame}
		\frametitle{Your title}
		Your text
	\end{frame}
```

environment. If you start a new section or subseciton, it will automatically appear in the *Overview* slide (which is automatically created at the beginngin of each section).

## How to use equations?

If you want to use equations or other mathematical entities, just import the packages as
```latex
	\usepackage{amsmath,amssymb,amsthm,mathrsfs,amsfonts,dsfont}
```

or the ones needed.