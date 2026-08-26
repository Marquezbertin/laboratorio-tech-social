# Módulo 04 — Ciência de Dados 📊

**Duração:** 90 min · **Precisa:** [Google Colab](https://colab.research.google.com/) (grátis, sem instalar).

## Objetivo
Usar Python para ler dados, entender padrões e contar histórias com números. Exemplo real: dados do [Esporte São Pedro](https://esportesaopedro.com.br/).

## 1. Carregando dados
```python
import pandas as pd

dados = pd.DataFrame({
    "time": ["Time A", "Time B", "Time C"],
    "gols": [12, 8, 15],
    "jogos": [6, 6, 6]
})
print(dados)
```

## 2. Análise simples
```python
dados["media_gols"] = dados["gols"] / dados["jogos"]
print(dados.sort_values("media_gols", ascending=False))
```

## 3. Visualizar
```python
import matplotlib.pyplot as plt

plt.bar(dados["time"], dados["gols"], color="#38bdf8")
plt.title("Gols por time")
plt.show()
```

## 4. Desafio — Seus dados
Escolha um tema da sua cidade (esporte, clima, transporte). Colete 10 linhas de dados em uma planilha e gere um gráfico no Colab.

## Próximo passo
Vá para o [`Módulo 05 — IoT & Nuvem`](modulo-05-iot-nuvem.md).
