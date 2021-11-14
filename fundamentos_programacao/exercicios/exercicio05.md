# Exercício 05

## Enunciado

Escreva um algoritmo que leia um valor inteiro e diga se ele é primo.

## Solução

```py

valor = int(input("Informe o valor a ser testado: "))

div = 0
for i in range(1, valor+1):
    if(valor % i == 0):
        div += 1 #conta os divisores do número

if(div <= 2):
    print("É PRIMO!")
else:
    print("NÃO É PRIMO!")

```

## Sobre

By: **will.i.am** | github.com/williampilger

2021.11.13 - Bom Princípio - RS

♪ Final Masquerade - Linkin Park

Curso: **Fundamentos de Programação**