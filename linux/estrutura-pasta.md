
# Exercício: Estrutura de pastas simulando uma empresa

## Objetivo
Simular a estrutura de diretórios de uma empresa fictícia (TechCorp),
com departamentos e rotinas de arquivos, praticando os comandos
básicos de manipulação de arquivos e diretórios no Linux.

## Estrutura final

\`\`\`
comercial/
├── clientes/
└── contratos/
diretoria/
├── documentos/
└── relatorios/
financeiro/
├── folha_pagamento/
├── notas_fiscais/
│   ├── fevereiro/NF_6729_25072026.txt
│   ├── janeiro/NF_4520
│   └── marco/NF_7622
└── relatorios/
rh/
├── contratos/joao_silva.txt
├── funcionarios/
│   ├── maria_souza.txt
│   └── pedro_lima.txt
└── recrutamento/
ti/
├── backups/sistema.log
├── documentacao/
├── logs/
│   ├── acesso.log
│   ├── erro.log
│   └── sistema.log
└── scripts/backup.sh
\`\`\`

## Comandos praticados
mkdir, touch, nano, cat, mv, cp, rm, rmdir, tree, cd, ls

## O que aprendi
- **`rm` não apaga diretórios** — só arquivos. Pra apagar pasta é preciso
  usar `rm -r` (remove com conteúdo) ou `rmdir` (só funciona se a pasta
  já estiver vazia).
- **Nomes de pasta com espaço** precisam de aspas (ex: `'notas fiscais'`),
  senão o terminal interpreta como dois argumentos separados.
- Ao usar `mv` sem especificar destino, o comando não executa como esperado —
  aprendi a checar a sintaxe correta com `mv --help` em vez de tentar adivinhar.
