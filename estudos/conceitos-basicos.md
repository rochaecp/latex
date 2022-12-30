# LaTex

## Arquivo .tex

O arquivo .tex é dividido em:

1. **Preâmbulo**: contém as informações globais do texto, como tipo de texto, quais imagens, fontes, etc
1. **Corpo do texto**: texto propriamente dito

Exemplo de arquivo .tex:

~~~tex
\documentclass[a4paper, 12pt]{article} %isto é o preambulo, article é o nome da classe, entre []s são as opçoes

\begin{document} %isto é o corpo do texto. Para cada \begin haverá um \end correspondente
    O texto vem aqui
\end{document}
~~~

## Comentários

#### Comentários de uma linha com: ```%```

~~~tex
% bom dia 
~~~

#### Comentários de múltiplas linhas

~~~tex
\begin{comment}
Comentário 
de
muitas
linhas
\end{comment}
~~~

## Quebra de linha

A barra dupla \\ é uma quebra de linha.  

~~~tex
\\
~~~

## Parágrafos

Uma ou muitas linhas em branco entre 2 linhas de texto marcam o fim de um parágrafo.    

## Espaços em branco

Caracteres “brancos” como espaços ou caracteres de tabulação (tabs) são tratados uniformemente como “espaços” pelo LATEX.  
Caracteres brancos consecutivos são tratados como um “espaço”.  
Espaços no inicio da linha são ignorados.  
Quebra de linha é lida como espaço em branco.  

## Diversos

O ficheiro contém o texto do documento assim como os comandos que dizem ao LATEX como formatar o texto.  
Tem que instalar os arquivos para português do babel: sudo apt-get install texlive-lang-portuguese  

## Comandos

Chaves {} são usadas para delimitar comandos.  

- a classe article tem formatações pré estabelecidas como margens e numeração de página

## Caracteres especiais (outros:  $  ^ & _ { } ~ \ # $)

~~~tex
\c c == ç 
\~a == ã
\'o == ó
\^o == ô
2$^\circ$ == 2°
~~~

## Formatações de texto

~~~tex
\begin{center}
    Texto centraliazado, outras opções: flushright, flushleft
\end{center}

\textbf{texto em negrito}
\textit{texto em itálico}
\underline{texto sublinhado}
~~~

## Inserindo alguns textos e a classe lipsum

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
