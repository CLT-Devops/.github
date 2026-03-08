## Titulo do PR (padrao)
<!--
Use um destes formatos:
Vx.y.z - [Label][Type] - Objetivo
Vx.y.z - [SI] - Objetivo
-->

## Issue relacionada
<!-- Obrigatorio. Ex.: Closes #123 -->
Closes #

## Objetivo e contexto
<!-- O problema que este PR resolve e por que agora -->

## O que mudou
- 
- 
- 

## Como validar
1. 
2. 
3. 

## Observabilidade e alertas
- correlation_id nos logs impactados:
- eventos/telemetria alterados:
- alerta Slack criado/ajustado:

## Risco e rollback
- Risco principal:
- Plano de rollback:

## Checklist DoD (obrigatorio)
- [ ] Escopo da issue foi entregue e validado
- [ ] Testes (unit/integration/e2e) cobrindo o fluxo alterado
- [ ] CI passou (lint, testes, checks de contrato quando aplicavel)
- [ ] Logs estruturados atualizados (com correlation_id quando aplicavel)
- [ ] Alertas Slack revisados/testados (quando aplicavel)
- [ ] Nao ha segredo/token hardcoded
- [ ] Sem breaking change nao documentada
- [ ] Documentacao atualizada (se aplicavel)
