# Arquivo .tex

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

## Diversos

O ficheiro contém o texto do documento assim como os comandos que dizem ao LATEX como formatar o texto.  
Tem que instalar os arquivos para português do babel: sudo apt-get install texlive-lang-portuguese  

## Comandos

Chaves {} são usadas para delimitar comandos.  

- a classe article tem formatações pré estabelecidas como margens e numeração de página