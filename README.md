```math
\documentclass{article}
\usepackage{tikz}
\usepackage{graphicx}

\usepackage{eso-pic}

\newcommand\BackgroundPic{
    \put(0,0){
        \parbox[b][\paperheight]{\paperwidth}{
            \vfill
            \centering
            \includegraphics[width=\paperwidth,height=\paperheight,keepaspectratio]{path/to/your/image.png}
            \vfill
        }
    }
}

\begin{document}

\AddToShipoutPicture*{\BackgroundPic}

Your main content goes here.

\end{document}
``
```