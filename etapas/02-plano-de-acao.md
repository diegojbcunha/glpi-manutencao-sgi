# Etapa 2 — Plano de Ação de Manutenção: Tarefas no GLPI

## O que foi realizado

Dentro de cada chamado, foram criadas **tarefas detalhadas** representando as ações corretivas e preventivas necessárias. Cada tarefa recebeu:

- Descrição clara da ação
- Responsável designado
- Prazo de entrega
- Status de acompanhamento (Pendente / Em andamento / Concluída)

---

## Tarefas por Chamado

### Chamado 1 — Desempenho Lento

| Tarefa | Responsável |
|--------|-------------|
| Analisar logs e identificar gargalos de desempenho | Matheus Ryan |
| Analisar código de geração de relatórios | Amanda Dantas |
| Refatorar consultas ao banco de dados | Matheus Ryan |

---

### Chamado 2 — Erros no Registro de Estoque

| Tarefa | Responsável |
|--------|-------------|
| Reproduzir e documentar os erros relatados | Amanda Erco |
| Analisar logs de erro do sistema | Jhonatas Barbosa |
| Corrigir código responsável pelo registro de entradas | Amanda Erco |

---

### Chamado 3 — Incompatibilidade com Ambientes Modernos

| Tarefa | Responsável |
|--------|-------------|
| Mapear navegadores e SOs afetados | Amanda Dantas |
| Atualizar bibliotecas front-end desatualizadas | Amanda Erco |
| Testar em diferentes ambientes (Chrome, Edge, Firefox, WinT1) | Jhonatas Barbosa |

---

### Chamado 4 — Segurança

| Tarefa | Responsável |
|--------|-------------|
| Realizar auditoria de segurança no sistema atual | Matheus Ryan |
| Pesquisar e selecionar bibliotecas de segurança atualizadas | Amanda Dantas |
| Implementar criptografia nos dados sensíveis | Jhonatas Barbosa |

---

### Chamado 5 — Integração PDV

| Tarefa | Responsável |
|--------|-------------|
| Levantar requisitos da integração com o PDV | Amanda Erco |
| Estudar API do sistema PDV disponível | Amanda Erco |
| Desenvolver módulo de integração | Jhonatas Barbosa |

---

## Por que essa etapa é importante?

O plano de ação transforma um problema abstrato em um **conjunto de ações concretas e mensuráveis**. Sem tarefas bem definidas, a equipe pode trabalhar de forma descoordenada, com duplicação de esforços ou esquecimento de etapas críticas.

A definição de **responsáveis e prazos** para cada tarefa cria accountability: cada membro da equipe sabe exatamente o que deve fazer e quando deve entregar.

O status das tarefas permite que gestores acompanhem o progresso em tempo real **sem precisar interromper a equipe técnica** com questionamentos frequentes.

### Como o GLPI auxiliou:
O sistema de tarefas do GLPI, integrado diretamente ao chamado, mantém o contexto completo de cada ação: quem fez, quando fez, quanto tempo gastou e qual foi o resultado. Isso é fundamental para **auditorias futuras** e para melhorar processos em projetos similares.

---

[← Diagnóstico](./01-diagnostico.md) | [Próxima Etapa: Cronograma →](./03-cronograma.md)
