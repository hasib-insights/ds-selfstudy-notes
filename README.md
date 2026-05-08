\begin{tikzpicture}[scale=0.8]  % scale পুরো ছবির সাইজ নিয়ন্ত্রণ করে
    % গ্রিড আঁকা (হালকা ধূসর রঙে, 0,0 থেকে 3,3 পর্যন্ত)
    \draw[step=0.5cm, gray, very thin] (0,0) grid (3,3);
    
    % অক্ষরেখা আঁকা (X এবং Y), তীরচিহ্নসহ
    \draw[->, thick] (0,0) -- (3.5,0) node[anchor=north] {$x$};
    \draw[->, thick] (0,0) -- (0,3.5) node[anchor=east] {$y$};
    
    % অক্ষের লেবেল বা নাম্বার বসানো (যেমন: 1,2)
    \foreach \x in {0,1,2,3}
        \draw (\x cm,1pt) -- (\x cm,-1pt) node[anchor=north] {$\x$};
    \foreach \y in {0,1,2,3}
        \draw (1pt,\y cm) -- (-1pt,\y cm) node[anchor=east] {$\y$};
