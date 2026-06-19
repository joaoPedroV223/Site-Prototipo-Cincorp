# Sistema Financeiro Local - Cincorp

Versão sem instalação, sem PostgreSQL e sem backend.

## Como usar

1. Extraia o ZIP.
2. Abra o arquivo `index.html` no navegador.
3. Use as páginas de Recibos, Protocolos, Tarefas, Histórico e Backup.

## Onde os dados ficam salvos

Os dados ficam no LocalStorage do navegador, neste computador.

Ficam registrados:

- último número de recibo usado;
- lotes de recibos emitidos/baixados;
- protocolos gerados/baixados;
- tarefas pendentes e concluídas;
- eventos recentes do sistema.

## Importante

- Outra pessoa em outro computador não verá estes dados automaticamente.
- Para levar os dados para outro computador, use a página Backup e exporte/importa o JSON.
- Protocolos com mais de 1 ano pela data de entrega são removidos automaticamente ao abrir o sistema.
- Não há login real nesta versão, pois tudo roda localmente no navegador.
