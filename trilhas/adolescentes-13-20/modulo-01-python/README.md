# Módulo 01 — Python & Lógica de Programação 🐍

**Duração:** 90 min · **Precisa:** Python 3 ou [Google Colab](https://colab.research.google.com/).

## Objetivo
Aprender os fundamentos da programação com Python: variáveis, laços, condições e funções.

## 1. Olá, mundo
```python
print("Olá, Makers! 🚀")
```

## 2. Variáveis e tipos
```python
nome = "Ana"
idade = 15
altura = 1.65
estudante = True

print(f"{nome} tem {idade} anos e é estudante: {estudante}")
```

## 3. Condições
```python
if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")
```

## 4. Laço (repetição)
```python
for i in range(5):
    print(f"Repetição {i + 1}")
```

## 5. Funções
```python
def saudacao(pessoa):
    return f"Oi, {pessoa}! Bem-vindo ao lab."

print(saudacao("Bruno"))
```

## Desafio — Calculadora de média
Crie um programa que recebe 3 notas, calcula a média e diz se o aluno passou (média >= 6).
```python
notas = [7.5, 8.0, 6.5]
media = sum(notas) / len(notas)
print(f"Média: {media:.2f}")
print("Aprovado!" if media >= 6 else "Reprovado!")
```

## Próximo passo
Vá para o [`Módulo 02 — Desenvolvimento Web`](../modulo-02-web/README.md).
