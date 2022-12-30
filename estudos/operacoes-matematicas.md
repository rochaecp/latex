# LaTex

Notações matemáticas: ```$ax^2 + bx + c = 0$```  
Notações matemáticas quebrando linha e centralizando: ```$$ax^2 + bx + c = 0$$```  

## Constantes

~~~tex
\pi
~~~

## Símbolos matemáticos

~~~tex
\neq             %not equal
\overline{AB}    %linha sobre AB = segmento AB
~~~

## Diversos Exemplos

~~~tex
%operações matemáticas básicas
\documentclass[a4paper, 12pt]{article}
\usepackage[top=2cm, bottom=2cm, left=2.5cm, right=2.5cm]{geometry}
\usepackage[utf8]{inputenc}
\usepackage{amsmath, amsfonts, amssymb}
\DeclareMathOperator{\sen}{sen} %{comando}{o que eu quero que ele substitua}
\DeclareMathOperator{\tg}{tg}

\begin{document}

$a + b$        %inserimos expressões matemáticas assim, ou assim: $$a + b$$

$a - b$

$a \cdot b$    %multiplicação com o ponto no meio!

$a \times b$ %multiplicação com simbolo correto    

$a \div b$     %divisao

$\frac{a}{b}$ %fração em 1 linha

$\dfrac{a}{b}$ %fração com mais de uma linha - usa os pacotes amsmath, amsfonts, amssymb

$\sqrt{a}$ %raiz quadrada

$\sqrt[3]{a}$ %raiz cubica

$a^{b+c}$ %potencia

$a_{1}$ %a com indice 1

$A = \{1; 2; 3; 4\}$ %trabalhando com conjuntos \{ para pegar { 

$A = \{1; \, 2; \, 3; \, 4\}$ %trabalhando com conjuntos - aumentando o espaço: \, outro \; e \

$B = \{ x \in \mathbb{Z}\}$ %x pertence aos inteiros

$B = \{ x \in \mathbb{Z} \, | \, -2 \leq x < 4  \}$ %x pertence aos inteiros

$C = \{ x \in \mathbb{N} \, | \, x \geq 2 \}$

$A \cap B$ %intessecção 

$C \cup B$  %união 

$A \subset B$ %está contido

$A \supset B$ %contém

$A \not\subset B$ %não está contido

$A \not\supset B$ %não contém

$A \not\in B$ %não pertence

$\forall x $ %para todo

$\exists x $ %existe 

$x = \textrm{texto aqui}$ %texto dentro do ambiente matemático

$\mathbb{R}^*_+$ 

$\varnothing$ %conjunto vazio

$f : \mathbb{R} \to \mathbb{R}$ %funcao

$\mapsto $ %outra seta

$f(x) = 
    \begin{cases}
        x^2 - 1; \, x \geq 1 \\ 
        2x + 1; \, x < 1 \\
    \end{cases}
$%barra dupla quebra a linha

$\log_2 x$ %logaritmo na base 2 de x

$\ln x$ %logaritmo natural de x

$\cos x$

$\sin x$

$\textrm{sen} \, x$

$\sen x$ %graças ao cabeçalho inserido em \DeclareMathOperator{\sen}{sen}

$\tg x$ %usa \DeclareMathOperator{\tg}{tg}

$ \left( \frac{\pi}{2} \right) $ %faz parenteses grande que cresce junto com a expressão dentro 

$ \left[\frac{\pi}{2} \right] $

$ \left\{\frac{\pi}{2} \right\} $

\end{document}
~~~