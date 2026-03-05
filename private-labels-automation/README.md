# Label automation (repo privado)

Este pacote deve ficar em um repositório **privado** de administracao (ex.: `org-automation`).

## Arquivos

- `.github/workflows/sync-org-labels.yml`
- `.github/labels.json`

## Secret necessario

Crie no repo privado o secret `ORG_LABELS_TOKEN`.

Permissoes minimas do token (fine-grained):

- `Metadata`: read
- `Issues`: write

## Execucao recomendada

1. Rode `workflow_dispatch` com `dry_run=true`.
2. Revise o log.
3. Rode novamente com `dry_run=false`.
4. Para modo estrito (manter apenas labels do arquivo), use `prune_unmanaged=true`.

## Observacao

`prune_unmanaged=true` remove labels existentes que nao estao no `.github/labels.json`.
