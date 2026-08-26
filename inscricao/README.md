# 📝 Formulário de Inscrição de Alunos

Formulário para inscrever crianças e adolescentes no Laboratório de Tecnologia Social, com **consentimento LGPD/ECA** do responsável.

## Backend de recebimento (já integrado)
O formulário (`index.html`) envia os dados via **AJAX** para o [Formspree](https://formspree.io) (gratuito).

### Passos para ativar (1 minuto)
1. Acesse https://formspree.io e crie uma conta gratuita.
2. Clique em **New form** e copie a URL (ex: `https://formspree.io/f/xblrgara`).
3. No arquivo `inscricao/index.html`, localize no início do `<script>`:
   ```js
   const FORM_ENDPOINT = "https://formspree.io/f/SEU_ENDPOINT_AQUI";
   ```
4. Substitua `SEU_ENDPOINT_AQUI` pela sua URL.
5. Faça commit/push. Pronto — as inscrições chegam por e-mail.

> Sem configurar o endpoint, o formulário avisa o erro na tela. Nenhum dado é enviado a lugar nenhum até você colar o endpoint.

## Alternativa: Google Forms
1. Crie o formulário em https://forms.google.com (nome, idade, trilha, responsável, e-mail, consentimento).
2. Em **Envio**, copie o link e compartilhe, ou incorpore no `index.html` via `<iframe>`.

## Onde fica publicado
GitHub Pages: `https://marquezbertin.github.io/laboratorio-tech-social/inscricao/`

## Privacidade
- Coletamos o mínimo necessário, com consentimento dos responsáveis.
- Dados de menores não são repassados a terceiros para marketing (LGPD / ECA).
