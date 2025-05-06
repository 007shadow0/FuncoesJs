# FuncoesJs
Definir e criar funções em Javascript utilizando os formatos: declaration, expression e arrow.

## Declaration

O jeito mais básico de definir funções em JavaScript é através da function declaration, toda função de declaração começa com a palavra reservada e obrigatória function, seguida pelo nome da função (também obrigatório) e uma lista de parâmetros (opcionais) separados por vírgula e encapsulados em parenteses (obrigatórios), o último passo é definir as chaves (obrigatórias) que será o corpo da função.
Exemplo:

![image](https://github.com/user-attachments/assets/4faf7c9b-9fc0-4887-8ffd-98ea6c152689)

Essa estrutura é a mais simples, porém, obrigatória para as functions declaration.Como mencionado anteriormente, também podemos definir parâmetros opcionais separados por vírgula

![image](https://github.com/user-attachments/assets/524c7716-4d14-48cc-bdd9-d94510edf93b)


**Vantagens**
.Hosting
.Legibilidade do código
.Facilidade de depuração

**Desvantagens**


**Exemplo 1**
Function square(numero){
	Return numero*numero;
}
**Exemplo 2**
(Declaração de funções em JavaScript são hoisted à definição de função. Pode usar uma função antes de tê-la declarada)
Hoisted();

Function hoisted(){
	Console.log(“FOO”);
}

**Exemplo 3**
Function nome (Vinícius){
	Console.log(‘nome’, Vinícius)
}
nome(‘Vinícius’)

###Expression
Uma expressão  de função (function expression) se difere de uma declaração de função tradicional na forma a qual declaramos um nome a uma variável podendo ser uma função anônima. a função de expressão pode ser lidada como uma qualquer expressão em JavaScript, por exemplo:
const nome = 'Vinícius
Nesse exemplo, estamos criando uma expressão onde definimos uma variável chamada nome e atribuímos uma String para ela.
Com as funções de expressão, podemos fazer algo muito semelhante:
const ola = function() {
    console.log('Olá')
}
ola()
Repare que é bem parecido com as funções de declaração, uma das sútis diferenças é que ela está sendo atribuída para uma variável, onde não definimos o nome da função e sim o nome da variável que irá referenciar a mesma.
 

**Vantagem**
Pode criar funções anônimas 
Legibilidade do código



**Desvantagem**
Não faz hosting
Depuração menos clara (caso seja uma função anônima)

**Exemplo 1**
var x= function (y){
	return y*y;
};

**Exemplo 2**
(Função anônima)
Let saudação= function (nome){
	Return ‘olá,$ {nome}!’;
};
Console.log(saudação ‘vinicius’);

**Exemplo 3**
const gerarnome= function(nome){
	return’ OI, meu nome é ${nome}’;
};
const vinicius=gerarnome(“Vinícius);
console.log(Vinícius);

