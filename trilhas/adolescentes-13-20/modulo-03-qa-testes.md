# Módulo 03 — Qualidade de Software (QA) ✅

**Duração:** 90 min · **Inspirado em:** [Despertar QA](https://www.despertarqa.net/).

## Objetivo
Aprender que "funcionar" não é sorte: é planejado, testado e garantido. Você vai pensar como um QA.

## O que é QA?
Quality Assurance = garantir que o software faça o que promete, sem quebrar e sem surpresas.

## 1. Plano de Teste (manual)
Para o site do Módulo 02, liste casos de teste:

| ID | O quê testar | Passos | Resultado esperado |
|----|--------------|--------|--------------------|
| T1 | Botão clica | Abrir site, clicar no botão | Título muda para "Você clicou! 🎉" |
| T2 | Responsivo | Reduzir janela | Texto continua legível |

## 2. Teste automatizado (Python + pytest)
Instale: `pip install pytest`

`test_site.py`:
```python
def titulo_inicial():
    return "Olá, Dev! 🚀"

def test_titulo_inicial():
    assert "Dev" in titulo_inicial()

def soma(a, b):
    return a + b

def test_soma():
    assert soma(2, 3) == 5
```

Rode: `pytest test_site.py`

## 3. Desafio — Bugs caçados
No repositório [listadetarefas_qualityAssurance](https://github.com/Marquezbertin/listadetarefas_qualityAssurance) há uma app de lista de tarefas com erros propositais. Encontre 3 bugs e descreva como corrigir.

## Próximo passo
Vá para o [`Módulo 04 — Ciência de Dados`](modulo-04-ciencia-dados.md).
