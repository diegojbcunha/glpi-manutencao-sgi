# Etapa 1 — Diagnóstico e Análise: Registro de Chamados no GLPI

## O que foi realizado

Foram criados **cinco chamados no GLPI**, cada um correspondendo a um problema identificado pelos gestores das lojas. Cada chamado foi preenchido com:

- Título descritivo
- Descrição detalhada do impacto
- Prioridade justificada
- Categoria
- Responsável atribuído

---

## Chamados Criados

| # | Título | Categoria | Prioridade |
|---|--------|-----------|------------|
| 1 | Desempenho lento no carregamento de dados e relatórios do SGI | Desempenho | 🔴 Alta |
| 2 | Erros ao registrar novas entradas de estoque no SGI | Erro | 🔴 Alta |
| 3 | Incompatibilidade do SGI com navegadores e SO modernos | Incompatibilidade | 🟡 Média |
| 4 | Ausência de recursos de segurança adequados no SGI | Segurança | 🔴 Alta |
| 5 | Solicitação de integração do SGI com sistema PDV | Nova Funcionalidade | 🟢 Baixa |

---

## Detalhamento dos Chamados

### Chamado 1 — Desempenho Lento
- **Impacto:** O sistema apresenta lentidão crítica no carregamento de dados e geração de relatórios, especialmente em horários de pico. O tempo de resposta está afetando diretamente a produtividade dos operadores das lojas, causando atrasos no atendimento e no controle de estoque.
- **Urgência:** Alta | **Impacto:** Médio | **Prioridade:** Alta

### Chamado 2 — Erros no Registro de Estoque
- **Impacto:** Usuários relatam falhas ao tentar registrar novas entradas de mercadorias no estoque. Os erros causam discrepâncias nos registros de inventário, comprometendo a integridade dos dados e podendo gerar prejuízos financeiros por divergência entre estoque físico e sistema.
- **Urgência:** Alta | **Impacto:** Alto | **Prioridade:** Alta

### Chamado 3 — Incompatibilidade com Ambientes Modernos
- **Impacto:** O sistema apresenta problemas de compatibilidade com versões atuais de navegadores (Chrome, Edge, Firefox) e sistemas operacionais mais recentes (Windows 11, macOS Ventura). Usuários com dispositivos modernos enfrentam falhas de interface e funcionalidades que não respondem corretamente.
- **Urgência:** Média | **Impacto:** Médio | **Prioridade:** Média

### Chamado 4 — Vulnerabilidades de Segurança
- **Impacto:** Foi identificado que o sistema SGI não possui mecanismos de segurança suficientes para proteger dados sensíveis de inventário e transações comerciais. A ausência de criptografia, controle de acesso granular e logs de auditoria expõe a empresa a riscos de vazamento de dados e acessos não autorizados.
- **Urgência:** Alta | **Impacto:** Alto | **Prioridade:** Alta

### Chamado 5 — Integração com PDV
- **Impacto:** Os gestores solicitaram a implementação de integração entre o SGI e o sistema de PDV utilizado nas lojas, com o objetivo de automatizar a atualização do estoque após cada venda realizada, eliminando a necessidade de lançamentos manuais e reduzindo erros operacionais.
- **Urgência:** Baixa | **Impacto:** Baixo | **Prioridade:** Baixa

---

## Por que essa etapa é importante?

O registro formal de chamados é o **ponto de partida** de qualquer processo de manutenção organizado. Sem um sistema de chamados, os problemas seriam tratados de forma informal, sem rastreabilidade, sem priorização adequada e sem histórico documentado.

A **priorização dos chamados** é especialmente crítica: ao classificar os problemas de segurança e desempenho como Alta prioridade, a equipe garante que os recursos sejam alocados primeiro onde o impacto no negócio é maior. A integração com PDV, sendo uma melhoria futura, recebeu prioridade baixa, evitando desperdício de recursos em algo que não bloqueia operações.

### Como o GLPI auxiliou:
O GLPI permitiu registrar cada problema com campos estruturados (título, descrição, prioridade, categoria e responsável), criando um **repositório centralizado e rastreável** de todos os problemas do SGI. Isso elimina a dependência de e-mails ou anotações informais, que frequentemente se perdem ou ficam desatualizadas.

---

[← Voltar ao README](../README.md) | [Próxima Etapa: Plano de Ação →](./02-plano-de-acao.md)
