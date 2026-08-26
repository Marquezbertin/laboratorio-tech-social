# 📝 Formulário de Inscrição de Alunos

Formulário para inscrever crianças e adolescentes no Laboratório de Tecnologia Social.

## O que tem no formulário
- Dados do aluno (nome, idade, trilha de interesse).
- Dados do responsável (obrigatório para menores de 18 anos).
- **Consentimento LGPD / ECA** para participação e uso de imagem.

## Como publicar
1. O arquivo `index.html` é o formulário pronto.
2. Para receber as inscrições, conecte a um backend gratuito:
   - **Google Forms** (mais simples): crie o formulário em forms.google.com e incorpora o link, ou
   - **Formspree** (formspree.io): grátis para poucos envios; cole o endpoint no `action` do form.
3. Hospede em `inscricao/` e ele já fica acessível pelo GitHub Pages em:
   `https://marquezbertin.github.io/laboratorio-tech-social/inscricao/`

> Por padrão o formulário abre o cliente de e-mail (mailto) para envio manual. Edite o `action` para automatizar.
