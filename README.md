```math
\documentclass{standalone}
\usepackage{tikz}
\usepackage{graphicx}
\usepackage{eso-pic}

\newcommand\BackgroundPic{
    \AtPageLowerLeft{
        \raisebox{-\height}{
            \includegraphics[width=\paperwidth,height=\paperheight,keepaspectratio]{path/to/your/image.png}
        }
    }
}

\AddToShipoutPicture*{\BackgroundPic}

\begin{document}

Your main content goes here.

\end{document}
``
```