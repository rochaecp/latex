# Classe Lipsum

~~~tex
\documentclass[a4paper, 12pt]{article} %10, 11 ou 12 são as opções de tamanho de letra para article
                                        %classe extarticle permite 14, 17 e 20, outra classe: book
\usepackage[top=2cm, bottom=2cm, left=2.5cm, right=2.5cm]{geometry}
\usepackage[utf8]{inputenc}
\usepackage{amsmath, amsfonts, amssymb}
\usepackage{lipsum} %para inserir textos lorem ipsum

\begin{document}

% Adicionando textos em diferentes blocos
Aqui vai um texto normal \lipsum[1]

\begin{quotation}
    Aqui vai um texto em quotation \lipsum[7]
\end{quotation}

\begin{quote}
    Aqui vai um texto em quote \lipsum[7]
\end{quote}


\end{document}
~~~