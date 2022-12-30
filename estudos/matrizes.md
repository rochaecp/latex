# LaTex - Matrizes

~~~tex
\documentclass[a4paper, 12pt]{article}
\usepackage[top=2cm, bottom=2cm, left=2.5cm, right=2.5cm]{geometry}
\usepackage[utf8]{inputenc}
\usepackage{amsmath, amsfonts, amssymb}


\begin{document}

$ 
\begin{bmatrix}
    1 & 2 & 3 \\
    4 & 5 & 6 \\
    7 & 8 & 9
\end{bmatrix}
$

$$\\$$ %pula uma linha

$ 
\begin{pmatrix}
    1 & 2 & 3 \\
    4 & 5 & 6 \\
    7 & 8 & 9 
\end{pmatrix}
$

$$\\$$ %pula uma linha

$ 
\begin{vmatrix}
    1 & 2 & 3 \\
    4 & 5 & 6 \\
    7 & 8 & 9 
\end{vmatrix}
$

$$\\$$ %pula uma linha

$\det A$

$m \times n$ %matriz m por n

$$\\$$ %pula uma linha

$ 
\begin{bmatrix}
    a_{11} & a_{12} & \cdots & a_{1n} \\
    a_{21} & a_{22} & \cdots & a_{2n} \\
    a_{31} & a_{32} & \cdots & a_{3n} \\
    \vdots & \vdots & \ddots & \vdots \\
    a_{m1} & a_{m2} & \cdots & a_{mn} 
\end{bmatrix}
$

$$\\$$ %pula uma linha


\end{document}
~~~