# FuncoesJs
Definir e criar funções em Javascript utilizando os formatos: declaration, expression e arrow.

## Declaration

O jeito mais básico de definir funções em JavaScript é através da function declaration, toda função de declaração começa com a palavra reservada e obrigatória function, seguida pelo nome da função (também obrigatório) e uma lista de parâmetros (opcionais) separados por vírgula e encapsulados em parenteses (obrigatórios), o último passo é definir as chaves (obrigatórias) que será o corpo da função.  
Exemplo:  
	![Declaration01](https://github.com/user-attachments/assets/7d99f27f-e33b-46f8-9979-3355ff69e8c6)


Essa estrutura é a mais simples, porém, obrigatória para as functions declaration.Como mencionado anteriormente, também podemos definir parâmetros opcionais separados por vírgula

![Declaration02](https://github.com/user-attachments/assets/b856fc8f-d5d7-4ec8-88e2-91fa76f1fe30)


## Vantagens
-Hosting.  
-Legibilidade do código.  
-Facilidade de depuração.  

## **Desvantagens**
-Hoisting, apesar de ajudar, pode causar problema em códigos maiores.  
-Sem função anônima.  

## **Exemplo 1**  
```javascript
Function square(numero){  
	Return numero*numero;
}  
```

## **Exemplo 2**  
```javascript
//Declaração de funções em JavaScript são hoisted à definição de função. Pode usar uma função antes de tê-la declarada
Hoisted();  

Function hoisted(){  
	Console.log(“FOO”);  
}  
```
## **Exemplo 3**  
```javascript
Function nome (Vinícius){  
	Console.log(‘nome’, Vinícius)  
}  
nome(‘Vinícius’)  
```
## Expression  
Uma expressão  de função (function expression) se difere de uma declaração de função tradicional na forma a qual 
declaramos um nome a uma variável podendo ser uma função anônima. A função de expressão pode ser lidada como uma qualquer expressão em JavaScript, por exemplo:  
```javascript
const nome = 'Vinícius  
```
Nesse exemplo, estamos criando uma expressão onde definimos uma variável chamada nome e atribuímos uma String para ela.
Com as funções de expressão, podemos fazer algo muito semelhante:  
```javascript
const ola = function() {  
    console.log('Olá')  
}  
ola()  
```
![Expression](https://github.com/user-attachments/assets/2241078f-2c7d-497f-acdf-8f0e5bd1b8d5)


Repare que é bem parecido com as funções de declaração, uma das sútis diferenças é que ela está sendo atribuída para uma variável, 
onde não definimos o nome da função e sim o nome da variável que irá referenciar a mesma.
 

## **Vantagem**  
-Pode criar funções anônimas.   
-Legibilidade do código.  



## **Desvantagem**  
-Não faz hosting.  
-Depuração menos clara (caso seja uma função anônima).  

## **Exemplo 1**  
```javascript
var x= function (y){  
	return y*y;  
};  
```
## **Exemplo 2** - Função anônima
```javascript 
Let saudação= function (nome){  
	Return ‘olá,$ {nome}!’;  
};
Console.log(saudação ‘vinicius’);  
```
## **Exemplo 3**  
```javascript
const gerarnome= function(nome){  
	return’ OI, meu nome é ${nome}’;  
};  
const vinicius=gerarnome(“Vinícius);  
console.log(Vinícius);  
```
## Arrow  
Uma expressão arrow function(funções de seta) tem uma sintaxe pequena, um dos motivos da 
criação desta função é facilitar a criação e utilização de funções em JavaScript, ou seja, elas permitem a criação de funções de maneira resumida. 
Em vez de function palavra-chave, ela usa uma seta (composta por dois sinais: = e >).


![Seta01](https://github.com/user-attachments/assets/585c33f0-865b-46b4-b531-812e01d74e13)

## Vantagens  
-Sintaxe pequena.  
-São anônimas.  


## Desvantagens.  
-Método de objetos.  
-Não faz hosting.  

## Exemplo 1 
```javascript
const n1 = Number(prompt("Digite o 1º número:"));
const n2 = Number(prompt("Digite o 2º número:"));

const soma = (a, b) => {
    return a + b;
};

console.log("Resultado da soma:", soma(n1, n2));
```
## exemplo 2
```javascript
const ola = () => {
    console.log("Olá, mundo!");
};

ola(); 
// Chamando a função para que ela seja executada
```
## exemplo 3
```javascript
const mult = (x, y) => {
    const valor = x * y;
    return valor;
};

console.log("Resultado da multiplicação:", mult(4, 5));
```
