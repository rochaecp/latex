# LaTex - Listas

~~~tex
\documentclass[a4paper, 12pt]{article}
\usepackage[top=2cm, bottom=2cm, left=2.5cm, right=2.5cm]{geometry}
\usepackage[utf8]{inputenc}

\begin{document}

\begin{center}
    \textbf{Lista numerada}
\end{center}


\begin{enumerate}
 \item um texto
     \begin{enumerate}
      \item um sub texto
        \begin{enumerate}
          \item um sub sub item hehe
          \item outro sub sub item haha
        \end{enumerate}
      \item outro subtextoo
     \end{enumerate}
 \item outro texto
 \item mais um
\end{enumerate}


\begin{center}
    \textbf{Lista não-numerada}
\end{center}

%lista nao numerada
\begin{itemize}
    \item um item feliz
        \begin{itemize}
            \item muito legal mano
            \item muito legal mesmo!
        \end{itemize}
    \item mais itens felizes
    \item maaais itens
\end{itemize}


\end{document}
~~~