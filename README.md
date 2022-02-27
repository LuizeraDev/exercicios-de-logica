# Exercícios em JavaScript

Exercicios de JavaScript — É para você que gostaria de aprender programação, não sabe nada ainda e quer iniciar direto na prática utilizando a linguagem JavaScript.

A motivação inicial foi numa tentativa de ensinar meus amigos a utilizarem o github.

# Índice

   * [Índice](#índice)
   * [Antes de qualquer coisa](#antes-de-qualquer-coisa)
      * [Abrindo o DevTools](#abrindo-o-devtools)
   * [Exercícios](#exercícios)
      * [1. Variáveis e Funções](#1-variáveis-e-funções)
         * [Exercício 1.1](#exercício-11)
         * [Exercício 1.2](#exercício-12)
         * [Exercício 1.3](#exercício-13)
         * [Exercício 1.4](#exercício-14)
      * [2. Condicionais (<em>if</em>, <em>else</em>)](#2-condicionais-if-else)
         * [Exercício 2.1](#exercício-21)
         * [Exercício 2.2](#exercício-22)
         * [Exercício 2.3](#exercício-23)
      * [3. Loop](#3-loop)
         * [Exercício 3.1](#exercício-31)
         * [Exercício 3.2](#exercício-32)
         * [Exercício 3.3](#exercício-33)
      * [4. Vetores (array)](#4-vetores-array)
         * [Exercício 4](#exercício-41)

# Antes de qualquer coisa

Antes de iniciar, precisamos de boas ferramentas para iniciar nossos trabalhos. O "feijão com o arroz" pra mim são as seguintes ferramentas:

 - DevTools, que está dentro do próprio navegador Chrome (apertando a tecla 'F12', na tela do navegador)

# Exercícios

## 1. Variáveis e Funções

### Exercício 1.1

Faça um programa que **exiba** 3 números na tela.

Dica - exibindo (ou "imprimindo") números na tela:

```javascript
var a = 23;
console.log(a);
```

### Exercício 1.2

Faça um programa que **leia** 3 números e **exiba**-os na tela.

Dica - lendo números:
```javascript
// abre uma janelinha com um "prompt" que lê um número digitado pelo
// usuário e atribui o resultado a variável "v1"
var v1;
v1 = Number(prompt ());
```

### Exercício 1.3

Faça um programa que **leia** 3 números, **some**-os e **exiba** a média entre eles.

Dica:
```
A média entre dois números, é a soma dos dois números divididos por 2
A média entre três números, é a some dos três números divididos por 3
A média entre 'n' números, é a some dos 'n' números divididos por 'n'
```

### Exercício 1.4

Faça um programa que leia do 5 números e some todos os números exibindo o resultado.

## 2. Condicionais (_if_, _else_)

### Exercício 2.1 

Faça um programa que leia 2 números, some-os e exiba uma mensagem com o resultado apenas **se** o resultado for maior que 100.

### Exercício 2.2

Para um jogo, precisamos saber se um personagem morreu ou não depois de sofrer um ataque. Faça uma função que receba 2 parâmetros, 'dano' e 'saude'. A função deve retornar '1' se o dano for matar o personagem (ou seja, deixar sua saúde menor ou igual a zero) e '0' caso contrário.

Dica - utilize a seguinte função:
```javascript
function personagemMorreu (dano, saude) {
  //
}
```

### Exercício 2.3

Precisamos limitar as posições em que um inimigo pode andar na tela. A menor posição possível é 0 e a maior, 100: qualquer valor maior que 100 ou menor que 0 sairia fora da tela. Precisamos de uma função LimitaPosicao que recebe uma POSICAO que pode ter qualquer valor positivo ou negativo, verifica se ela é válida ou não e retorna sempre um valor corrigido entre 0 e 100.

Dica - utilize a seguinte função:
```javascript
function limitaPosicao (posicao) {
  // código da função
}
```

## 3. Loop

### Exercício 3.1

Escreva um programa que o usuário digite o número da tabuada desejada e também até onde é o limite de repetições calcule e mostre a tabuada digitado pelo usuário.

### Exercício 3.2

Escreva um programa que realize uma P.A (Progressão Aritmética) de dois em dois começando do número 1 até o número 37.

### Exercício 3.3

Escreva um progrma que realize uma P.G (Progressão Geométrica) multiplicando sempre por 3 começando do número 1 até o número 729.

## 4. Vetores (array)

### Exercício 4.1
Faça um programa que leia um vetor numérico de 10 posições. Depois, ordene o vetor em ordem crescente e apresente os elementos ordenados.
