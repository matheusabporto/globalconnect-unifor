# E7 — Backlog Refinado em User Stories

**Projeto:** GlobalConnect Unifor — Sistema de Gestão da Mobilidade Acadêmica Internacional  
**Disciplina:** Requisitos e Modelagem de Sistemas  
**Curso:** Análise e Desenvolvimento de Sistemas — Unifor (2026.1)  
**Entregável:** 7 de 10  
**Prazo:** 18/05 a 22/05/2026  

---

## O que este entregável apresenta

| # | Conteúdo | Descrição |
|---|----------|-----------|
| 01 | **O que é uma User Story** | O formato que usamos para descrever cada funcionalidade do sistema sob a perspectiva do usuário final. |
| 02 | **Foco no MVP** | Por que escolhemos refinar apenas as 7 funcionalidades Must Have que compõem o Produto Mínimo Viável. |
| 03 | **As 7 User Stories** | Cada feature Must Have transformada em User Story com critérios de aceitação claros. |
| 04 | **Próximo passo** | Como o backlog refinado prepara o protótipo de alta fidelidade no Figma. |

---

## 📖 O que é uma User Story

Uma **User Story** é uma descrição curta de uma funcionalidade do sistema, vista pela perspectiva de quem vai usá-la. É o formato padrão de comunicação entre equipes de produto e equipes de desenvolvimento em metodologias ágeis.

### Formato canônico

> **Como** [tipo de usuário],  
> **quero** [ação ou funcionalidade],  
> **para** [benefício ou valor que isso gera].

### Exemplo aplicado ao GlobalConnect

> **Como** estudante da Unifor,  
> **quero** verificar automaticamente se atendo aos pré-requisitos do intercâmbio,  
> **para** saber se posso me candidatar sem precisar ir presencialmente ao NEI.

---

## 🎯 Foco no MVP — 7 Features Must Have

### Por que focar só nas Must Have?

Em projetos reais, refinamos primeiro o que será construído. As Should Have e Could Have permanecem no backlog e serão refinadas em ciclos futuros, quando estivermos mais perto de implementá-las. Isso evita desperdício de esforço com detalhes que podem mudar antes da implementação.

### As 7 funcionalidades que compõem o nosso MVP:

| ID | Feature |
|----|---------|
| **F1.1** | Portal centralizado de oportunidades |
| **F1.2** | Verificação automática de elegibilidade |
| **F2.1** | Upload digital de documentos |
| **F2.2** | Checklist interativo de documentos |
| **F3.1** | Painel de status da candidatura |
| **F3.2** | Notificações automáticas de prazos |
| **F4.1** | Painel administrativo do NEI |

---

## 📘 As 7 User Stories Detalhadas

### US-01 · F1.1 — Portal Centralizado

> **Como** estudante da Unifor interessado em intercâmbio,  
> **quero** acessar um portal centralizado com todas as informações sobre o programa,  
> **para** encontrar tudo o que preciso em um único lugar, sem ter que pesquisar em várias páginas do site.

**Critérios de Aceitação:**
- ✓ O portal deve exibir todos os pré-requisitos, prazos e instituições parceiras em uma única página.
- ✓ O conteúdo deve ser acessível sem necessidade de login institucional.
- ✓ Deve haver um menu visível com as seções principais (sobre, requisitos, parceiras, prazos, FAQ).

---

### US-02 · F1.2 — Verificação Automática de Elegibilidade

> **Como** estudante da Unifor,  
> **quero** verificar automaticamente se atendo aos pré-requisitos do intercâmbio,  
> **para** saber se posso me candidatar sem precisar ir presencialmente ao NEI.

**Critérios de Aceitação:**
- ✓ O sistema deve cruzar dados do histórico acadêmico do aluno (matrícula, % do curso, média global e reprovações).
- ✓ O resultado deve indicar claramente se o aluno está apto ou não, com checklist visual dos 5 critérios.
- ✓ Caso não atenda algum critério, o sistema deve informar exatamente qual requisito falhou.

---

### US-03 · F2.1 — Upload Digital de Documentos

> **Como** estudante candidato ao intercâmbio,  
> **quero** enviar todos os documentos exigidos de forma digital pela plataforma,  
> **para** não precisar ir presencialmente ao NEI entregar documentos físicos.

**Critérios de Aceitação:**
- ✓ O sistema deve aceitar upload de arquivos PDF, JPG e PNG com até 5 MB cada.
- ✓ Cada documento enviado deve receber confirmação visual imediata na interface.
- ✓ O aluno deve poder substituir um documento enviado antes da análise oficial pelo NEI.

---

### US-04 · F2.2 — Checklist Interativo de Documentos

> **Como** estudante candidato ao intercâmbio,  
> **quero** ver um checklist visual com todos os documentos exigidos e seu status,  
> **para** saber exatamente o que já enviei e o que ainda falta para concluir minha candidatura.

**Critérios de Aceitação:**
- ✓ O checklist deve listar todos os documentos exigidos com indicação de enviado (☑) ou pendente (☐).
- ✓ Uma barra de progresso deve mostrar quantos documentos foram enviados em relação ao total.
- ✓ Documentos pendentes devem ser destacados visualmente para chamar atenção do aluno.

---

### US-05 · F3.1 — Painel de Status da Candidatura

> **Como** estudante com candidatura em andamento,  
> **quero** acompanhar em tempo real o status da minha candidatura ao intercâmbio,  
> **para** saber em qual etapa do processo estou sem precisar entrar em contato com o NEI.

**Critérios de Aceitação:**
- ✓ O painel deve exibir uma timeline com todas as etapas do processo (inscrição até embarque).
- ✓ A etapa atual deve estar visualmente destacada, com as anteriores marcadas como concluídas.
- ✓ Cada etapa concluída deve mostrar data, horário e responsável pela atualização.

---

### US-06 · F3.2 — Notificações Automáticas de Prazos

> **Como** estudante candidato ao intercâmbio,  
> **quero** receber notificações automáticas sobre prazos e atualizações da candidatura,  
> **para** não perder nenhuma data importante e ficar sabendo de mudanças sem precisar checar manualmente.

**Critérios de Aceitação:**
- ✓ O sistema deve enviar notificações por e-mail e por push (no app mobile) sobre eventos relevantes.
- ✓ O aluno deve poder escolher quais tipos de notificação receber (prazos, status, mensagens).
- ✓ Notificações de prazos devem ser enviadas com 7 dias, 3 dias e 1 dia de antecedência.

---

### US-07 · F4.1 — Painel Administrativo do NEI

> **Como** analista do NEI,  
> **quero** visualizar todas as candidaturas ativas em um painel administrativo centralizado,  
> **para** gerenciar o processo de forma eficiente sem ter que consultar sistemas separados.

**Critérios de Aceitação:**
- ✓ O painel deve listar todas as candidaturas com filtros por status, curso e instituição de destino.
- ✓ Cada candidatura deve permitir acesso rápido aos documentos enviados e ao histórico do aluno.
- ✓ O analista deve poder aprovar ou solicitar correção de documentos diretamente no painel.

---

## 📊 Resumo do Backlog Refinado

| Métrica | Valor |
|---------|-------|
| User Stories detalhadas | **7** |
| Critérios de aceitação definidos | **21** |
| Personas envolvidas | **2** (Estudante e Analista do NEI) |
| Cobertura do MVP | **100%** |

---

## 💡 Pronto para implementação

Cada User Story está descrita com clareza, com critérios de aceitação objetivos que permitem verificar quando a funcionalidade está pronta. Esse nível de detalhe permite que uma equipe de desenvolvimento comece a construir o sistema sem dúvidas sobre o que deve ser entregue.

---

## 🔗 Conexão com entregáveis anteriores

Cada User Story conecta-se diretamente aos entregáveis anteriores:

| Entregável | Conexão |
|-----------|---------|
| **E3** — Matriz de Dores | Cada US resolve dores identificadas nas respostas reais. |
| **E4** — Mapa de Jornada | As USs cobrem as etapas críticas da jornada do estudante. |
| **E5** — Backlog MoSCoW | Cada US deriva diretamente de uma feature Must Have. |
| **E6** — Protótipo Lo-Fi | As USs US-02, US-03, US-04 e US-05 já têm wireframes prontos. |

---

## ➡️ Próximo passo

**E8 — Protótipo de Alta Fidelidade (Figma)**

No próximo entregável, vamos transformar os wireframes lo-fi em **telas finais navegáveis no Figma**, com:
- Aplicação completa da paleta visual Ocean Gradient
- Tipografia, ícones e elementos de UI definitivos
- Protótipo navegável que simula o fluxo completo do usuário
- Componentes reutilizáveis para garantir consistência visual

---

*Documento gerado como parte do Projeto de Extensão — Requisitos e Modelagem de Sistemas (2026.1)*
