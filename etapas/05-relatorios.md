# Etapa 5 — Relatórios: Geração de Relatórios no GLPI

## O que foi realizado

Foram gerados relatórios no GLPI para acompanhar o andamento do projeto de manutenção, incluindo:

- Listagem de chamados por prioridade, categoria e status
- Estatísticas globais da equipe
- Relatório de conclusão das atividades

---

## Relatórios Gerados

| Relatório | Caminho no GLPI | Finalidade |
|-----------|-----------------|------------|
| **Chamados por Status** | Assistência > Chamados > Filtro: Status | Visão geral de chamados abertos, em andamento e fechados |
| **Chamados por Prioridade** | Assistência > Chamados > Filtro: Prioridade | Identificar chamados críticos que precisam de atenção imediata |
| **Chamados por Categoria** | Assistência > Chamados > Filtro: Categoria | Analisar distribuição dos problemas por tipo |
| **Estatísticas Globais** | Assistência > Estatísticas | Tempo médio de resolução, volume de chamados, desempenho da equipe |
| **Relatório de Conclusão** | Chamados com status "Solucionado" | Documentar formalmente o encerramento de cada problema |

---

## Resultado Final dos Chamados

Ao final do projeto, todos os 5 chamados foram encerrados com status **Fechado**:

| # | Chamado | Prioridade | Categoria | Status |
|---|---------|------------|-----------|--------|
| 5 | Solicitação de integração do SGI com PDV | 🟢 Baixa | Nova Funcionalidade | ✅ Fechado |
| 4 | Ausência de recursos de segurança no SGI | 🔴 Alta | Segurança | ✅ Fechado |
| 3 | Incompatibilidade do SGI com ambientes modernos | 🟡 Média | Incompatibilidade | ✅ Fechado |
| 2 | Erros ao registrar novas entradas de estoque | 🔴 Alta | Erro | ✅ Fechado |
| 1 | Desempenho lento no carregamento de dados e relatórios | 🔴 Alta | Desempenho | ✅ Fechado |

---

## Métricas Geradas

As estatísticas do GLPI permitiram acompanhar:

- **Número de chamados** abertos, solucionados, atrasados e fechados ao longo do tempo
- **Tempo médio** de fechamento, solução e duração real por chamado
- **Pesquisa de satisfação** dos solicitantes ao final de cada atendimento

---

## Por que essa etapa é importante?

Os relatórios são a etapa que **transforma dados operacionais em informação gerencial**. Sem relatórios, os gestores dependem de opiniões subjetivas da equipe técnica para saber se os problemas estão sendo resolvidos. Com relatórios, as decisões são baseadas em **fatos**.

- A **listagem por prioridade** permite identificar rapidamente se os problemas mais críticos estão recebendo atenção adequada
- O **acompanhamento do tempo** gasto em cada chamado é fundamental para calcular o custo da manutenção e justificar investimentos futuros em prevenção
- O **relatório de conclusão** documenta formalmente que cada problema foi resolvido, servindo como evidência em auditorias

### Como o GLPI auxiliou:
O GLPI oferece recursos nativos de filtragem e estatísticas que permitem gerar relatórios **sem necessidade de ferramentas externas**. A integração entre chamados, tarefas e projetos garante que todos os dados estejam consistentes e atualizados, gerando relatórios confiáveis para a tomada de decisões.

---

[← Comunicação](./04-comunicacao.md) | [Voltar ao README →](../README.md)
