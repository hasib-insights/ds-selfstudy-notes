\documentclass{article}
\usepackage{tikz}
\usetikzlibrary{arrows.meta}

\begin{document}
\begin{tikzpicture}[scale=0.8]
    % 1. গ্রিড
    \draw[step=0.5cm, gray, very thin] (0,0) grid (3,3);
    
    % 2. অক্ষরেখা
    \draw[->, thick] (0,0) -- (3.5,0) node[anchor=north] {$x$};
    \draw[->, thick] (0,0) -- (0,3.5) node[anchor=east] {$y$};
    
    % 3. অক্ষের নাম্বার
    \foreach \x in {0,1,2,3}
        \draw (\x cm,1pt) -- (\x cm,-1pt) node[anchor=north] {$\x$};
    \foreach \y in {0,1,2,3}
        \draw (1pt,\y cm) -- (-1pt,\y cm) node[anchor=east] {$\y$};
    
    % 4. ভেক্টর v = (1,2)
    \draw[->, line width=0.5mm, blue] (0,0) -- (1,2) node[midway, above, sloped, font=\small] {$\vec{v} = \begin{bmatrix} 1 \\ 2 \end{bmatrix}$};
    
    % 5. শেষ বিন্দুতে ডট
    \filldraw[black] (1,2) circle (2pt) node[above right] {$(1,2)$};
    
\end{tikzpicture}
\end{document}
