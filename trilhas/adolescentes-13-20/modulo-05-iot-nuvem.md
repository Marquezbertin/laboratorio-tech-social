# Módulo 05 — IoT & Computação em Nuvem ☁️

**Duração:** 90 min · **Inspirado em:** formação em IoT e Nuvem do criador do lab.

## Objetivo
Conectar o mundo físico à internet e entender como a nuvem guarda e processa dados.

## Conceitos
- **IoT (Internet das Coisas):** objetos com sensores que enviam dados pela internet.
- **Nuvem:** computadores poderosos na internet onde guardamos e processamos dados.
- **API:** "porteiro" que deixa um app pedir dados de outro.

## Exemplo — Lendo uma API (Python)
```python
import requests

resposta = requests.get("https://api.github.com/repos/Marquezbertin/laboratorio-tech-social")
dados = resposta.json()
print("Estrelas:", dados["stargazers_count"])
print("Descrição:", dados["description"])
```

## Projeto — Estação meteorológica caseira
1. Use um sensor de temperatura conectado a um microcontrolador.
2. Envie os dados para um serviço gratuito na nuvem (ex: ThingSpeak).
3. Crie uma página que mostra a temperatura da sua cidade em tempo real.

> Desafio: cruze com dados públicos abertos da sua cidade e publique um painel no GitHub Pages.

## Próximo passo
Vá para o [`Módulo 06 — Projeto Social`](modulo-06-projeto-social.md).
