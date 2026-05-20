# Manutenção de Software com GLPI

> Roteiro de prática desenvolvido para a disciplina de **Manutenção de Sistemas** do curso Técnico em Desenvolvimento de Sistemas — SENAI CIMATEC

---

##  Sobre o Projeto

Este repositório documenta o processo completo de manutenção do **Sistema de Gestão de Inventário (SGI)** de uma rede de lojas de materiais de construção, utilizando o **GLPI** (Gestionnaire Libre de Parc Informatique) como ferramenta central de gerenciamento.

O SGI apresentava **cinco problemas críticos** que foram tratados como chamados individuais no GLPI, cada um com análise, plano de ação, cronograma e comunicação adequados.

---

## Autores

| Nome | GitHub |
|------|--------|
| Amanda Dantas Laudelino | — |
| Diego José Barbosa da Cunha | — |
| Matheus Ryan Alves Santos | — |

📅 Data: 15/05/2026 · SENAI CIMATEC · Técnico em Desenvolvimento de Sistemas

---

## Problemas Identificados no SGI

| # | Problema | Categoria | Prioridade |
|---|----------|-----------|------------|
| 1 | Desempenho lento no carregamento de dados e relatórios | Desempenho | 🔴 Alta |
| 2 | Erros ao registrar novas entradas de estoque | Erro | 🔴 Alta |
| 3 | Incompatibilidade com navegadores e SOs modernos | Incompatibilidade | 🟡 Média |
| 4 | Ausência de recursos de segurança adequados | Segurança | 🔴 Alta |
| 5 | Necessidade de integração com sistema PDV | Nova Funcionalidade | 🟢 Baixa |

---

## Estrutura do Repositório

```
glpi-manutencao-sgi/
│
├── README.md                  # Este arquivo
│
├── etapas/
│   ├── 01-diagnostico.md      # Etapa 1 — Registro de Chamados no GLPI
│   ├── 02-plano-de-acao.md    # Etapa 2 — Plano de Ação e Tarefas
│   ├── 03-cronograma.md       # Etapa 3 — Gerenciamento de Projetos
│   ├── 04-comunicacao.md      # Etapa 4 — Comunicação e Netiqueta
│   └── 05-relatorios.md       # Etapa 5 — Geração de Relatórios
│
└── docs/
    └── roteiro-pratica.pdf    # Documento original do roteiro
```

---

## Fluxo do Processo de Manutenção

```
┌─────────────────┐
│  1. DIAGNÓSTICO │  → Registro dos 5 chamados no GLPI com prioridade e categoria
└────────┬────────┘
         ▼
┌─────────────────┐
│ 2. PLANO DE     │  → Tarefas detalhadas com responsável, prazo e status
│    AÇÃO         │
└────────┬────────┘
         ▼
┌─────────────────┐
│ 3. CRONOGRAMA   │  → Projeto de 45 dias com 5 etapas vinculadas aos chamados
└────────┬────────┘
         ▼
┌─────────────────┐
│ 4. COMUNICAÇÃO  │  → Acompanhamentos formais dentro de cada chamado
└────────┬────────┘
         ▼
┌─────────────────┐
│ 5. RELATÓRIOS   │  → Dados operacionais transformados em informação gerencial
└─────────────────┘
```

---

## Ferramenta Utilizada

**[GLPI — Gestionnaire Libre de Parc Informatique](https://glpi-project.org/)**

Ferramenta open source de gestão de serviços de TI, utilizada para:
- Registro e gerenciamento de chamados
- Criação de tarefas e planos de ação
- Gerenciamento de projetos com cronograma
- Registro de comunicações (Acompanhamentos)
- Geração de relatórios e estatísticas

---

## Cronograma Geral do Projeto

| Etapa | Período | Chamados |
|-------|---------|----------|
| Diagnóstico e Análise | 12/05 – 16/05 | 1, 2, 3, 4, 5 |
| Correção de Erros Críticos | 17/05 – 27/05 | 1, 2 |
| Segurança e Compatibilidade | 22/05 – 06/06 | 3, 4 |
| Desenvolvimento Integração PDV | 22/05 – 26/06 | 5 |
| Testes Finais e Encerramento | 21/06 – 26/06 | 1, 2, 3, 4, 5 |

**Prazo total: 45 dias**

---

## Benefícios do GLPI Demonstrados

| Aspecto | Benefício |
|---------|-----------|
| Organização | Centralização de chamados, tarefas e comunicações em um único sistema |
| Priorização | Classificação por prioridade garante foco nos problemas de maior impacto |
| Comunicação | Acompanhamentos no chamado eliminam dispersão em e-mails e WhatsApp |
| Decisões | Relatórios transformam dados operacionais em informação gerencial |
| Rastreabilidade | Histórico completo serve como evidência e base para melhorias futuras |

---

## Licença

Este projeto é de caráter educacional. Desenvolvido como atividade prática para o SENAI CIMATEC — 2026.
