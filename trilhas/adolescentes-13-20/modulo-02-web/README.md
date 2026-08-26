# Módulo 02 — Desenvolvimento Web 🌐

**Duração:** 90 min · **Precisa:** editor de texto (VS Code) e navegador.

## Objetivo
Construir um site responsivo usando HTML (estrutura), CSS (estilo) e JavaScript (interatividade).

## Estrutura de arquivos
```
modulo-02-web/
├── index.html
├── style.css
└── script.js
```

Veja os arquivos completos: [`index.html`](index.html), [`style.css`](style.css), [`script.js`](script.js).

## HTML (estrutura)
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Meu Site</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1 id="titulo">Olá, Dev!</h1>
  <button id="botao">Clique</button>
  <script src="script.js"></script>
</body>
</html>
```

## CSS (estilo)
```css
body { font-family: sans-serif; background: #0f172a; color: #e2e8f0; text-align: center; padding: 40px; }
button { background: #38bdf8; border: none; padding: 12px 24px; border-radius: 8px; cursor: pointer; }
```

## JavaScript (interatividade)
```javascript
document.getElementById("botao").addEventListener("click", () => {
  document.getElementById("titulo").textContent = "Você clicou! 🎉";
});
```

## Desafio
Crie um site para um projeto da sua comunidade (clube de esportes, ONG, biblioteca). Publique no GitHub Pages.

## Próximo passo
Vá para o [`Módulo 03 — Qualidade de Software (QA)`](../modulo-03-qa-testes.md).
