# Bhaskara

## Enunciado

Desenvolva um algoritmo que leia do teclado os valores para **A**, **B**, e **C**, e com Bhaskara calcule **X1** e **X2**.

## Solução

```py

from math import sqrt

print(" Calculadora de Bhaskara\n")
print("    x = (b ± sqrl(b**2 -4*a*c)) / ( 2*a )\n")

a = float(input("    Informe o valor de A: "))
b = float(input("    Informe o valor de B: "))
c = float(input("    Informe o valor de C: "))

delta = b**2 - 4*a*c

if( a!=0 and delta >= 0 ):
    raiz_delta = sqrt(delta)

    x1 = (-b + raiz_delta) / (2*a)
    x2 = (-b - raiz_delta) / (2*a)

    print("X1 =", x1)
    print("X2 =", x2)
else:
    print("Delta é negativo, ou A é zero!")

```

## Sobre

By: **will.i.am** | github.com/williampilger

2021.11.13 - Bom Princípio - RS

♪ Blood Brothers - Iron Maiden

Curso: **Fundamentos de Programação**