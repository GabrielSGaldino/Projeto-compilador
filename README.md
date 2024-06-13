# Atividade Avaliativa em Grupo

Como atividade avaliativa final da UC os alunos devem desenvolver os elementos
principais de um compilador. A proposta desta atividade é a implementação das
etapas front-end do projeto de uma linguagem de programação, ou seja, as
primeiras etapas da construção do compilador da linguagem específica.
A linguagem utilizada será o MiniJava (Java Simplificado).
1. Gramática livre de contexto e autômatos finitos
2. Analisador léxico
3. Analisador sintático
4. Analisador semântico

### ETAPA 1
Gramática Livre de Contexto e Autômatos finitos

A partir das definições da linguagem específica e da sugestão de uma sintaxe (final do arquivo), construir a gramática livre de contexto correspondente.

Construir os autômatos para cada classe de elementos do vocabulário terminal da linguagem: letras, dígitos, números, identificadores, operadores, palavras reservadas, pontuação, comentários.

### ETAPA 2 – Analisador léxico
Desenvolver um programa que realize a análise léxica.

A partir de um arquivo contendo um código (programa) em MiniJava, o analisador léxico deverá produzir um arquivo com os tokens identificados e seus valores correspondentes.
Cada linha do arquivo de saída deve conter um token reconhecido.

Fazer uso do que foi implementado na Etapa#1.

O analisador léxico deve ser capaz de lidar com os erros léxicos encontrados no programa. A mensagem de erro, “ERRO LÉXICO” juntamente com a sequência lexicamente errada, devem ser apresentadas e todo o processo finalizado.

### ETAPA 3 – Analisador sintático
Construir um programa que realize a análise siEtapa 3 - Analisador Sintático
Produzir as árvores de derivação de um dos termos da linguagem testados na
análise léxica.

### Etapa 4 - Analisador Semântico
Código ou trecho de código valide a árvore de derivação de uma palavra reservada de um comando
