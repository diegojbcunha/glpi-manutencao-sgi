# Etapa 3 — Cronograma de Manutenção: Gerenciamento de Projetos no GLPI

## O que foi realizado

Foi criado um **projeto no GLPI** chamado _"Manutenção e Evolução do Sistema SGI"_, com prazo total de **45 dias**. O projeto foi organizado em cinco etapas principais, cada uma correspondendo a um conjunto de chamados e tarefas. Os chamados foram vinculados ao projeto para permitir uma visão consolidada do andamento geral.

---

## Cronograma do Projeto

| # | Etapa | Início | Fim | Chamados Relacionados |
|---|-------|--------|-----|-----------------------|
| 1 | Diagnóstico e Análise | 12/05 | 16/05 | 1, 2, 3, 4, 5 |
| 2 | Correção de Erros Críticos | 17/05 | 27/05 | 1, 2 |
| 3 | Segurança e Compatibilidade | 22/05 | 06/06 | 3, 4 |
| 4 | Desenvolvimento Integração PDV | 22/05 | 26/06 | 5 |
| 5 | Testes Finais e Encerramento | 21/06 | 26/06 | 1, 2, 3, 4, 5 |

---

## Visualização do Cronograma (Diagrama de Gantt simplificado)

```
MAIO                               JUNHO
12  16  17        27  22        06  22        26  21  26
|---|---|---------|---|----------|---|---------|---|---|
████                                                    1. Diagnóstico e Análise
    ████████████████                                    2. Correção de Erros Críticos
                ████████████████████                    3. Segurança e Compatibilidade
                ████████████████████████████████        4. Desenvolvimento PDV
                                         ████████       5. Testes Finais e Encerramento
```

---

## Projeto no GLPI

**Nome:** Manutenção e Evolução do Sistema SGI  
**Status:** Em andamento (Processing)  
**Prioridade:** Média  
**Gerente:** glpi (administrador)  
**Abertura:** 12/05/2026

---

## Por que essa etapa é importante?

O gerenciamento de projetos é essencial para garantir que todas as atividades de manutenção sejam concluídas dentro do **prazo e do orçamento**. Um cronograma bem definido permite:

- Identificar dependências entre tarefas
- Alocar recursos de forma eficiente
- Antecipar riscos antes que virem problemas

A **vinculação dos chamados ao projeto** é uma funcionalidade poderosa do GLPI: ela permite que gestores vejam, em uma única tela, o status de todos os problemas sendo resolvidos simultaneamente, sem precisar abrir cada chamado individualmente. Isso é essencial para tomada de decisões rápidas em situações de pressão.

### Como o GLPI auxiliou:
O módulo de projetos do GLPI (`Ferramentas > Projetos`) oferece uma visão macro do projeto, com:
- Percentual de conclusão
- Datas planejadas versus reais
- Vínculos diretos com os chamados

Isso **transforma dados isolados em inteligência gerencial**.

---

[← Plano de Ação](./02-plano-de-acao.md) | [Próxima Etapa: Comunicação →](./04-comunicacao.md)
