```math

\documentclass{article}
\usepackage{background}
\usepackage{graphicx} % Required for including images
\usepackage{xcolor} % Required for color

\backgroundsetup{
  scale=1,
  color=red,
  opacity=0.1,
  angle=0,
  position=current page.south,
  vshift=0pt,
  hshift=0pt,
  contents={\includegraphics[width=\paperwidth,height=\paperheight]{path/to/your/image.png}}
}

\begin{document}
\BgThispage
Your content goes here.
\end{document}
``
```