# ProjetoJs
 Projeto com todo o conteúdo do curso 

# Sobre variáveis 

Espaços na memória que guardam algum valor (dados). Variáveis servem para guardar dados.

## Nomes de variáveis

* Podem começar com: letra, $ ou _

* Não podem começar com números

* Pode-se usar tanto letras quanto números

* É possivel usar acentos e símbolos

* Não podem conter espaços

* Não podem ser palavras reservadas. Palavras que desenpenham alguma função no JS com "function", "let", etc

### Dicas para nomes de variáveis

* Os nomes são case sensitive, ou seja, tem difença ao usar letras maiúsculas e minúsculas

* Ter variáveis com nomes coerentes, o nome da variável diz respeito a sua função. Nunca colocar um nome que não tenha nenhuma relação com a sua função no código, isso ajuda você a entender melhor o seu código

## Tipos primitivos primordiais de variáveis

* O JavaScript não diferencia números reais de números inteiros, para o JS todos são do tipo "number"

* Cadeias de caracteres que são chamadas de variáveis do tipo "string", além de letras e palavras serem strings, um conjunto de números também é uma string como um número de telefone, CPF, etc

* Variáveis que só podem receber os valores de "true" ou "false" ,variáveis interruptores, são chamadas de variáveis do tipo "boolean"

### typeoff

Comando que nos ajuda descobrir qual o tipo da variável. Ex: typeoff nome da variável, dado, objeto, vetor, valor, etc.

## Sinais no JavaScript e suas funções

= : Recebe

== : Igual de mesmo valor

=== : Igual de mesmo valor e tipo

 Sinal de + : Soma ou Concatenação. Será soma quando os valores somados forem do tipo "number" e será concatenação quando os valores somados forem do tipo "string".

 ## Conversão em JS

 Number(n) : Converte uma string para um número

 parseInt : Converte uma string para um número inteiro somente

 parseFloat :  Converte uma string para um número real

 String(valor) : Converte um number para uma string

 valor.toString() : Converte um number para uma string, exatamente igual o de cima, só muda a sintaxe 

 ### Template string

 Entre crase, permite usar variáveis dentro de uma string.  string ${variável} string `

 ### Algumas funcionalidades extras

 #### Formatação de strings

* string.lenght : quantos caracteres a string tem

* string.toUpperCase() : todas a lestras ficam maiúsculas

* string.toLowerCase() : todas letras ficam minúsculas

#### Formatação de numbers

* number.toFixed(número de casa desejadas) : limita o número de acordo com as casa desejadas

* number.replace('caracter', 'troca o "caracter" ') :troca alguma coisa (primeiro '') por outra (segundo ''). Pode ser utilizado com qualquer caracter, mas é muito comumm utilizado para trocar o "." por "," para exibir resultados de acordo com o sistema numérico brasileiro

* number.toLocaleString('lingua - PAÍS', {style: 'currency', currency: 'Qual a moeda'}) : faz com que o number passe a usar a moeda do país desejado (R$, $,etc).  

*Usando isso para colocar um número em reais (R$) temos: 

    number.toLocaleString('pt - BR', {style: 'currency', currency: 'BRL'})

## Ordem de operadores

Para os operadores aritiméticos a ordem dá conta é igual a da matemática

Quando temos mais de um tipo de operadores juntos o programa segue a seguinte ordem: 1°: Aritiméticos. 2°: Relacionais. 3°: Lógicos. 4°: Ternários, são sempre os últimos.

Quando se tem mais de um operador lógico na expressão segue essa ordem: 1°: Não. 2°: E. 3°: OU.

## Operadores ternários

São operadores que trabalham com três operandos, por isso o nome ternário.

Consiste em: teste?'true':'false'

O operador ternário sempre testa algo e retorna algum valor pré-definido quando esse valor for verdadeiro ou quando for falso.

O "teste" sempre tem que ser um boolean e é o local em que fica a condição. O "true" é um valor pré definido e é oque acontece caso o teste retorne verdadeiro. O "false" é também um valor pré definido e é oque acontece caso o teste retorne falso.