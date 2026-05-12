# E6 — Protótipo de Baixa Fidelidade

**Projeto:** GlobalConnect Unifor — Sistema de Gestão da Mobilidade Acadêmica Internacional  
**Disciplina:** Requisitos e Modelagem de Sistemas  
**Curso:** Análise e Desenvolvimento de Sistemas — Unifor (2026.1)  
**Entregável:** 6 de 10  
**Prazo:** 11/05 a 15/05/2026  

---

## O que este entregável apresenta

| # | Conteúdo | Descrição |
|---|----------|-----------|
| 01 | **Critério de escolha** | Por que prototipamos 3 funcionalidades específicas do MVP e quais dores reais cada uma resolve. |
| 02 | **Os 6 wireframes** | 3 funcionalidades em duas plataformas: versão web (desktop) e versão mobile. |
| 03 | **Resumo e próximos passos** | O que esse protótipo cobre do MVP e como ele prepara o terreno para o protótipo de alta fidelidade no Figma. |

---

## 🎯 Critério de escolha das telas prototipadas

Escolhemos prototipar as **3 funcionalidades Must Have mais críticas** do MVP, que atacam diretamente as dores reais identificadas nas respostas do Guilherme e do Thiago.

### 🔍 F1.2 — Verificação Automática de Elegibilidade
**Por quê:** É a porta de entrada do aluno no sistema. Sem essa funcionalidade, o aluno não sabe se pode se candidatar.  
**Dor que resolve:**
> *"Não consegui entender por onde começar."* — Guilherme `[Resposta Real]`

### 📤 F2.1 + F2.2 — Upload Digital de Documentos com Checklist
**Por quê:** É o coração do sistema. Substitui completamente o atendimento presencial no NEI por um fluxo 100% digital.  
**Dor que resolve:**
> *"Obter e validar documentos é a etapa mais difícil. Quero entregar tudo online."* — Thiago `[Resposta Real]`

### 📡 F3.1 — Painel de Status da Candidatura
**Por quê:** Resolve a ansiedade gerada pela espera. Dá transparência total do processo ao aluno em tempo real.  
**Dor que resolve:**
> *"Quero ver meu status pelo celular."*

---

## 🖼️ Os 6 Wireframes

### Wireframe 1 — Verificação de Elegibilidade (F1.2)

**Função:** Onde o aluno descobre se está apto a se candidatar ao intercâmbio.

**Versão Web (Desktop):**
- Coluna esquerda: dados acadêmicos do aluno carregados automaticamente do sistema da Unifor
- Coluna direita: resultado da análise com checklist visual dos 5 pré-requisitos
- Cálculo automático cruza histórico acadêmico + CPF do aluno
- Botão principal: "Iniciar Candidatura →"

📁 `wf1_web_elegibilidade.png`

**Versão Mobile:**
- Layout vertical com card de resultado destacado no topo
- Lista de dados acadêmicos simplificada
- Pré-requisitos em formato de lista compacta
- Botão fixo no rodapé acima da tab bar de navegação

📁 `wf1_mobile_elegibilidade.png`

---

### Wireframe 2 — Upload Digital de Documentos (F2.1 + F2.2)

**Função:** O coração do sistema. Substitui o atendimento presencial por um fluxo 100% online.

**Versão Web (Desktop):**
- Barra de progresso da candidatura no topo (6 de 10 documentos enviados)
- Coluna esquerda: checklist completo com status de cada documento (☑ enviado / ☐ pendente)
- Coluna direita: área de upload com drag-and-drop tracejado
- Validação automática de formato exibida em tempo real

📁 `wf2_web_documentos.png`

**Versão Mobile:**
- Card de progresso no topo
- Cada documento aparece como card individual
- Botão "Enviar" claramente destacado nos documentos pendentes
- Botão "Continuar candidatura" fixo no rodapé

📁 `wf2_mobile_documentos.png`

---

### Wireframe 3 — Painel de Status da Candidatura (F3.1)

**Função:** Dá ao aluno visibilidade total do processo, eliminando a ansiedade da espera.

**Versão Web (Desktop):**
- Timeline horizontal com 6 etapas do processo (Inscrição → Visto)
- Etapas concluídas preenchidas, atuais destacadas, futuras em branco
- Coluna esquerda: detalhes da etapa atual + histórico de eventos com datas
- Coluna direita: resumo do destino, período e coordenador
- Botões de ação: "Falar com NEI" e "Baixar comprovante"

📁 `wf3_web_status.png`

**Versão Mobile:**
- Card de destino destacado no topo
- Timeline vertical adaptada para leitura em scroll
- Cada etapa com data e status
- Botão "Falar com o NEI" fixo no rodapé

📁 `wf3_mobile_status.png`

---

## 📊 Resumo do Protótipo

| Métrica | Valor |
|---------|-------|
| Funcionalidades Must Have prototipadas | **3** |
| Wireframes (web + mobile) | **6** |
| Plataformas validadas | **2** (desktop e mobile) |
| Cobertura do MVP | **100%** (3 das 7 Must Have, cobrindo as etapas críticas) |

---

## 💡 Por que esse protótipo é suficiente

As 3 funcionalidades prototipadas cobrem as **etapas mais críticas da jornada do aluno**:

1. **Descoberta** (Elegibilidade) — onde o aluno entra no sistema
2. **Candidatura** (Upload de Documentos) — onde está o maior volume de dor
3. **Acompanhamento** (Status) — onde está a ansiedade da espera

Validamos a **estrutura visual e o fluxo de navegação** antes de partir para o design final no Figma. Isso reduz retrabalho e garante que o produto final atenda às dores reais identificadas nas entrevistas com Guilherme e Thiago.

---

## ➡️ Próximo passo

**E7 — Backlog Refinado (User Stories)**

No próximo entregável, vamos transformar cada feature do backlog em **User Stories** detalhadas, no formato:
> *"Como [tipo de usuário], quero [ação], para [benefício]."*

Cada User Story terá critérios de aceitação claros, preparando o terreno para o protótipo de alta fidelidade no Figma (E8).

---

*Documento gerado como parte do Projeto de Extensão — Requisitos e Modelagem de Sistemas (2026.1)*  
*Wireframes lo-fi gerados programaticamente em escala de cinza para validação estrutural.*
