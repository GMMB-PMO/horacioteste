HORÁCIO — ARQUIVOS PARA PUBLICAÇÃO NO GITHUB PAGES

ESTRUTURA
- index.html: página inicial do site (precisa ficar na raiz do repositório).
- styles.css: estilos visuais.
- app.js: funcionalidades, navegação, FAQ e consulta de alocação.
- config.js: configuração; já está preparada para usar dados.json.
- dados.json: base local com as perguntas frequentes.
- modelo-perguntas.csv: cópia da base em formato CSV para edição/importação.

COMO PUBLICAR
1. Abra o repositório https://github.com/GMMB-PMO/horacioteste
2. Na aba Code, envie/substitua TODOS os arquivos acima diretamente na raiz do repositório.
3. Confirme que o arquivo se chama exatamente index.html (minúsculo) e não está dentro de uma pasta.
4. Faça commit das alterações na branch main.
5. Em Settings > Pages, confirme: Deploy from a branch / main / /(root).
6. Aguarde o GitHub Actions concluir a publicação.
7. Abra https://gmmb-pmo.github.io/horacioteste/ e atualize com Ctrl+F5.

IMPORTANTE
- Não envie apenas o README. O index.html precisa estar na raiz.
- Não renomeie app.js, styles.css, config.js ou dados.json: os arquivos estão conectados entre si.
- A Consulta de Alocação contém somente os 30 termos finais aprovados, em ordem alfabética. Pitstop e Atendimento de Comentários – Retrabalho não aparecem nessa consulta.
- O conteúdo das orientações deve ser validado com o responsável pelo processo antes de uso oficial.
