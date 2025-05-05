# FuncoesJs
Definir e criar funções em Javascript utilizando os formatos: declaration, expression e arrow.

## Declaration

O jeito mais básico de definir funções em JavaScript é através da function declaration, toda função de declaração começa com a palavra reservada e obrigatória function, seguida pelo nome da função (também obrigatório) e uma lista de parâmetros (opcionais) separados por vírgula e encapsulados em parenteses (obrigatórios), o último passo é definir as chaves (obrigatórias) que será o corpo da função.
Exemplo:

![image](https://github.com/user-attachments/assets/4faf7c9b-9fc0-4887-8ffd-98ea6c152689)

Essa estrutura é a mais simples, porém, obrigatória para as functions declaration.

### Vantagens
.Hosting
.Legibilidade do código
.Facilidade de depuração

#### Desvantagens


#####Exemplo 1
Function square(numero){
	Return numero*numero;
}
#######Exemplo 2
(Declaração de funções em JavaScript são hoisted à definição de função. Pode usar uma função antes de tê-la declarada)
Hoisted();

Function hoisted(){
	Console.log(“FOO”);
}

########Exemplo 3
Function nome (Vinícius){
	Console.log(‘nome’, Vinícius)
}
nome(‘Vinícius’)

#########Expression
