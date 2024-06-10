```math
\documentclass{article}
\usepackage{tikz}
\usepackage{graphicx}
\usepackage{eso-pic}

\newcommand\BackgroundPic{
    \AtPageLowerLeft{
        \includegraphics[width=\paperwidth,height=\paperheight]{path/to/your/image.png}
    }
}

\AddToShipoutPicture*{\BackgroundPic}

\begin{document}

Your main content goes here.

\end{document}
``
```