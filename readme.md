# Projeto Netlify — VISA • Classificação de Risco por CNAE

Arquivos incluídos (coloque todos na **mesma pasta** no Netlify):
- `index.html` — Aplicação pronta para rodar.
- `cnae.json` — Base (carregada automaticamente).
- `revisaorisco_atualizado_corrigido.json` — Revisado/Atual (carregado automaticamente).

Ao abrir o site:
1. A Base e o Revisado são carregados automaticamente (se os arquivos estiverem presentes).
2. Em seguida, o sistema aciona automaticamente **Sincronizar CONCLA (IBGE)** para padronizar denominações e incluir CNAEs ausentes como **Nível I**.

> Observação: caso algum arquivo não seja encontrado, a aplicação continua funcionando e você poderá importar manualmente.
