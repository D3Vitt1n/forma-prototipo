# FORMA — Protótipo empresarial

Landing page estática de impressão 3D para empresas e indústrias. Aplicações ilustrativas; viabilidade técnica e valores definidos no atendimento.

## Publicar no GitHub Pages
1. Crie um repositório público chamado `forma-prototipo` na sua conta do GitHub.
2. Envie os arquivos desta pasta para a raiz da branch `main`. O `index.html` deve ficar diretamente na raiz, sem uma pasta intermediária.
3. Acesse Settings > Pages.
4. Em Build and deployment, escolha Deploy from a branch.
5. Selecione a branch `main`, a pasta `/(root)` e clique em Save.
6. Aguarde o deploy terminar. O endereço esperado nesta conta é https://d3vitt1n.github.io/forma-prototipo/ — ele só funcionará após a publicação.

Não precisa de npm, Node.js ou GitHub Actions personalizado. O GitHub publica HTML, CSS, JavaScript e SVG embutido diretamente. O arquivo `.nojekyll` desativa processamento Jekyll.

## Testar localmente
Abra `index.html` no navegador.

## Editar
- index.html: conteúdo e formulário
- style.css: identidade e responsividade
- app.js: catálogo ilustrativo, filtros, detalhes e WhatsApp

O WhatsApp informado está em `phone` no app.js e ficará visível no código público e nos links do site. Nenhum formulário é enviado automaticamente; os visitantes revisam a mensagem no WhatsApp.

## Verificação
JavaScript validado com node --check. Links de CSS e JavaScript são relativos, compatíveis com o caminho /forma-prototipo/.

Documentação: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
