# sicp-js
Prática dos conceitos abordados no livro SICP (Structure and Interpretation of Computer Programs) utilizando a Linguagem Javascript

# Anotações

---------------------------------------------------------

function quadrado(x) {
    return x * x;
}

function somaDosQuadrados(x,y) {
    return quadrado(x) + quadrado(y);
}

function f(a) {
    return somaDosQuadrados(a + 1, a * 2);
}

f(5);

--------------------------------------------------------

function maiorOuIgual (x,y) {
    return x > y || x === y;
}

maiorOuIgual(5,5);

--------------------------------------------------------

# Exercicios

#Exercicio 1.1

