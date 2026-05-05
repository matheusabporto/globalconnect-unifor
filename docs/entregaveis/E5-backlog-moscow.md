# E5 — Backlog Inicial Priorizado (MoSCoW)

**Projeto:** GlobalConnect Unifor — Sistema de Gestão da Mobilidade Acadêmica Internacional  
**Disciplina:** Requisitos e Modelagem de Sistemas  
**Curso:** Análise e Desenvolvimento de Sistemas — Unifor (2026.1)  
**Entregável:** 5 de 10  
**Prazo:** 04/05 a 08/05/2026  

---

## O que este entregável apresenta

| # | Conteúdo | Descrição |
|---|----------|-----------|
| 01 | **O método MoSCoW** | A técnica de priorização que vamos usar para classificar todas as funcionalidades do sistema. |
| 02 | **Visão geral dos 4 Épicos** | Os grandes blocos funcionais do sistema, cada um conectado a uma fase da jornada do usuário. |
| 03 | **Backlog detalhado por Épico** | As 17 features do sistema, classificadas por prioridade e ligadas às dores reais identificadas. |
| 04 | **Resumo da priorização** | Quantas features de cada categoria, e o que define o nosso MVP (Produto Mínimo Viável). |

---

## 🧭 O método MoSCoW

| Categoria | Significado | Explicação |
|-----------|-------------|-----------|
| 🔴 **Must Have** | Essencial | Sem essa funcionalidade, o sistema não cumpre seu objetivo principal. São os requisitos mínimos do MVP. |
| 🟠 **Should Have** | Importante | Gera valor relevante para o usuário, mas pode ser implementada após o lançamento inicial. |
| 🟢 **Could Have** | Desejável | Melhoria incremental que agrega valor à experiência, mas não é essencial para o funcionamento. |
| ⚪ **Won't Have** | Fora do escopo | Funcionalidades reconhecidas como ideias, mas que não entram nesta versão. Podem ser exploradas no futuro. |

---

## 📦 Visão Geral dos 4 Épicos

| Épico | Título | Descrição | Features |
|-------|--------|-----------|----------|
| **E1** | 🔍 Descoberta e Elegibilidade | Ajuda o aluno a descobrir o programa e verificar se atende os requisitos sem precisar ir ao NEI presencialmente. | 4 |
| **E2** | 📤 Candidatura e Documentação Digital | Digitaliza todo o processo de envio de documentos e a inscrição formal do aluno no programa. | 5 |
| **E3** | 📡 Acompanhamento e Comunicação | Oferece painel de status em tempo real, notificações automáticas e canal de comunicação com o NEI. | 4 |
| **E4** | 🏛️ Gestão Institucional | Painéis administrativos para o NEI e coordenadores: validação automática de elegibilidade e gestão de convênios. | 4 |

---

## 📘 Backlog Detalhado

### Épico 1 — Descoberta e Elegibilidade
*Funcionalidades para o aluno descobrir o programa e checar elegibilidade*

| ID | Feature | Descrição | Prioridade |
|----|---------|-----------|------------|
| F1.1 | Portal centralizado de oportunidades | Página única que reúne todas as informações sobre o programa, parceiras e prazos. | 🔴 **Must Have** |
| F1.2 | Verificação automática de elegibilidade | Sistema cruza dados do histórico do aluno e informa se ele atende os pré-requisitos. | 🔴 **Must Have** |
| F1.3 | Filtro de instituições por curso e país | Aluno filtra parceiras por área do seu curso, país de destino e idioma exigido. | 🟠 **Should Have** |
| F1.4 | Calculadora de custos estimados | Estima custos da experiência (taxa, tradução, passagem) com base no destino escolhido. | 🟢 **Could Have** |

### Épico 2 — Candidatura e Documentação Digital
*Funcionalidades para digitalizar todo o processo de candidatura*

| ID | Feature | Descrição | Prioridade |
|----|---------|-----------|------------|
| F2.1 | Upload digital de documentos | Aluno envia toda a documentação online, sem precisar ir ao NEI presencialmente. | 🔴 **Must Have** |
| F2.2 | Checklist interativo de documentos | Lista visual com cada documento exigido, o que está enviado e o que falta. | 🔴 **Must Have** |
| F2.3 | Validação automática de formato dos arquivos | Sistema verifica se os arquivos estão no formato correto antes de aceitar o envio. | 🟠 **Should Have** |
| F2.4 | Pagamento integrado da taxa de inscrição | Pagamento da taxa de R$ 556 dentro do próprio sistema, com confirmação automática. | 🟠 **Should Have** |
| F2.5 | Assinatura digital de termos de responsabilidade | Aluno e responsável assinam digitalmente os termos exigidos no processo. | 🟢 **Could Have** |

### Épico 3 — Acompanhamento e Comunicação
*Funcionalidades de transparência e comunicação ao longo do processo*

| ID | Feature | Descrição | Prioridade |
|----|---------|-----------|------------|
| F3.1 | Painel de status da candidatura | Aluno acompanha em tempo real cada etapa do processo seletivo no celular ou web. | 🔴 **Must Have** |
| F3.2 | Notificações automáticas de prazos | Alertas por e-mail ou push sobre prazos de inscrição e pendências de documentos. | 🔴 **Must Have** |
| F3.3 | Chat direto com o NEI | Canal de mensagens para tirar dúvidas com a equipe do NEI sem precisar ir presencialmente. | 🟠 **Should Have** |
| F3.4 | Espaço de relatos de ex-intercambistas | Área onde alunos que já fizeram intercâmbio compartilham experiências e dicas. | 🟢 **Could Have** |

### Épico 4 — Gestão Institucional (NEI e Coordenação)
*Funcionalidades para o NEI, coordenadores e DAE gerirem o programa*

| ID | Feature | Descrição | Prioridade |
|----|---------|-----------|------------|
| F4.1 | Painel administrativo do NEI | Visualização centralizada de todas as candidaturas, status e documentação dos alunos. | 🔴 **Must Have** |
| F4.2 | Painel do coordenador do curso | Coordenadores acompanham alunos do curso em mobilidade e validam equivalências. | 🟠 **Should Have** |
| F4.3 | Gestão de convênios com parceiras | Cadastro e atualização das 135+ instituições parceiras com vagas e requisitos. | 🟠 **Should Have** |
| F4.4 | Relatórios institucionais automáticos | Geração de relatórios sobre perfil dos candidatos e destinos mais procurados. | 🟢 **Could Have** |

---

## 📊 Resumo da Priorização

| Categoria | Quantidade | Percentual |
|-----------|------------|------------|
| 🔴 Must Have | **7** | 41% |
| 🟠 Should Have | **6** | 35% |
| 🟢 Could Have | **4** | 24% |
| **Total** | **17** | 100% |

---

## 🎯 Nosso MVP — Produto Mínimo Viável

As **7 funcionalidades** classificadas como **Must Have** formam o nosso MVP. Com elas, o sistema já cumpre seu objetivo principal: digitalizar a candidatura ao intercâmbio e dar visibilidade do processo aos estudantes e ao NEI.

### Composição do MVP:
- **F1.1** — Portal centralizado de oportunidades
- **F1.2** — Verificação automática de elegibilidade
- **F2.1** — Upload digital de documentos
- **F2.2** — Checklist interativo de documentos
- **F3.1** — Painel de status da candidatura
- **F3.2** — Notificações automáticas de prazos
- **F4.1** — Painel administrativo do NEI

As demais 10 funcionalidades (Should Have e Could Have) serão implementadas em versões posteriores, conforme o feedback de uso e a disponibilidade de tempo do projeto.

---

## 📌 Conexão com os entregáveis anteriores

Cada feature está conectada a uma dor real identificada:

- **Dores das Etapas 1 e 2** da jornada (E4) → **Épico 1**
- **Dores das Etapas 3, 4 e 5** da jornada (E4) → **Épico 2**
- **Dor da Etapa 6** da jornada (E4) → **Épico 3**
- **Dores levantadas pelos perfis de gestão** (E3) → **Épico 4**

---

## ➡️ Próximo passo

**E6 — Protótipo de Baixa Fidelidade das features Top 3**

No próximo entregável, vamos prototipar visualmente as 3 features mais críticas do MVP usando wireframes simples (papel ou ferramenta digital de baixa fidelidade), permitindo validar o fluxo de uso antes do design final.

---

*Documento gerado como parte do Projeto de Extensão — Requisitos e Modelagem de Sistemas (2026.1)*
