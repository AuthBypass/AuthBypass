```math
\documentclass{article}
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

\AddToShipoutPicture*{\BackgroundPic}

\begin{document}

Your main content goes here.

\end{document}
``
```