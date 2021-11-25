# Exercício 12

## Enunciado

Elabore um programa que lê valores inteiros para uma matriz a[6][6]. Calcule, a seguir, a soma dos elementos das colunas e linhas, escrevendo estes resultados em dois vetores. Escreva os vetores resultantes.

## Solução

```py

N = 6

from random import random
mat = []
for i in range(N):
    vet = []
    for j in range(N):
        vet.append(int(random()*1000))
    mat.append(vet)

print("A matriz é:")
for linha in mat:
    print(linha)

vet_somaLinhas = []
vet_somaColunas = []
for linha in range(N):
    for coluna in range(N):
        
        valor = mat[linha][coluna]

        if(coluna == 0):
            vet_somaLinhas.append(valor)
        else:
            vet_somaLinhas[linha] += valor
        
        if(linha == 0):
            vet_somaColunas.append(valor)
        else:
            vet_somaColunas[coluna] += valor

print(f"A soma das LINHAS é: {vet_somaLinhas}")
print(f"A soma das COLUNAS é: {vet_somaColunas}")

```

## Sobre

By: **will.i.am** | github.com/williampilger

2021.11.?? - Bom Princípio - RS

♪ ? - ?

Curso: **Fundamentos de Programação**