# LaTex

## Inserindo links para o próprio documento

~~~tex
\documentclass[a4paper, 12pt]{article} 
\usepackage[top=2cm, bottom=2cm, left=2.5cm, right=2.5cm]{geometry}
\usepackage[utf8]{inputenc}
\usepackage{amsmath, amsfonts, amssymb}
\usepackage{graphicx} %pacote para inserir figuras
\usepackage{float} %força posicionamento da figura - para usar: subtituir [htb] por[H]
\usepackage[brazil]{babel} %força latex a escrever figura e não figure
\usepackage{indentfirst} %identa o primeiro parágrafo após uma seção
\usepackage{lipsum}

\begin{document}

\section{Nome da seção}
\lipsum[10]

\section*{Nome da seção} %seçao sem numeração - nao aparece nas referências
\lipsum[10]


\end{document}
~~~