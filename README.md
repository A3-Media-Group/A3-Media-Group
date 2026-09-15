# A3 Media Group — site institucional

Site estático com páginas independentes para Início, Serviços, Portfólio, Sobre Nós e Contato. Os HTML publicados funcionam sem instalação ou compilação.

## Visualizar e verificar

- `npm install` instala as ferramentas de desenvolvimento.
- `npm start` abre o servidor em http://127.0.0.1:4173.
- `npm test` verifica páginas em desktop e mobile, navegação, imagens e contato usando Microsoft Edge instalado.
- `npm run build` regenera os HTML a partir de `scripts/build.cjs` e `scripts/projects.json`.

## Publicação

Envie os HTML, `assets`, `css`, `js`, `robots.txt` e `sitemap.xml` para a raiz da hospedagem. O domínio dos metadados permanece https://a3mediagroup.com.br/, já presente no original e acessível durante a revisão. Não são necessários Node.js nem backend na hospedagem. A publicação não foi realizada nesta revisão.

## Manutenção

- Conteúdo e estrutura: `scripts/build.cjs`.
- Projetos e links: `scripts/projects.json`.
- Aparência: `css/style.css`.
- Menu e contato: `js/script.js`.
- Imagens do portfólio: capturas reais de 15/09/2026, em `assets/img/projeto-*.jpg`.
- Contato: WhatsApp e e-mail preservados do original. O formulário abre uma mensagem no WhatsApp para revisão e envio pelo visitante. Não há envio automático ou banco de dados.

Consulte `REVISAO.md` para o diagnóstico editorial e os limites da validação.
