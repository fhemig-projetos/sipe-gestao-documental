# Implementação do Processo de Gestão e Digitalização da Pasta Funcional  
## Alinhamento SEI–SIPE | FHEMIG

Perfeito — o contexto está muito bem descrito e já revela maturidade de visão de processo.

Este documento estrutura a proposta em **quatro camadas**, para facilitar tanto o entendimento quanto o uso prático:

1. Premissas e princípios do processo (SEI + SIPE)  
2. Macrovisão do plano de ação (fases / subprojetos)  
3. Plano de ação detalhado (formato de tabela – a ser consolidado)  
4. Sugestões estratégicas e pontos de atenção  

A ideia é que este material funcione como **documento-base do projeto**, evitando retrabalho ou reinvenção futura.

---

## 1. Premissas e princípios  
### (Alinhados ao SIPE e à realidade da FHEMIG)

Antes da definição do plano de ação, é fundamental explicitar algumas premissas, que são essenciais para a **governança do processo**.

### 1.1 Premissas normativas e sistêmicas

- O **SEI-MG** é o repositório oficial dos documentos digitais.
- O **SIPE não armazena documentos**:
  - Atua apenas como sistema de **indexação**;
  - Aponta para documentos e processos existentes no SEI.
- A **Pasta Funcional Eletrônica (PFE)**:
  - É criada a partir da **admissão do servidor**;
  - Em regra, é representada por um **Processo SEI** (ou conjunto lógico de processos);
  - Contém documentos classificados como **020.5 – Assentamentos Individuais**.
- Após a adesão ao SIPE:
  - Não devem ser incluídos novos documentos em **pasta física** (regra geral);
  - O acervo físico passa a ser **legado**, com política de preservação até sua digitalização.

### 1.2 Premissas organizacionais da FHEMIG

- Alto volume de documentos físicos.
- Forte **descentralização** nas unidades hospitalares.
- Necessidade de:
  - Padronização;
  - Escalonamento;
  - Priorização (não é viável digitalizar todo o acervo de uma vez).
- Forte dependência e articulação com:
  - **SEPLAG / SUGESP** (gestão do SIPE);
  - **Subdigital** (governança do processo de digitalização);
  - **Benchmarking** com outros órgãos finalísticos.

Essas premissas orientam diretamente o desenho do plano de ação.

---

## 2. Macrovisão do plano de ação  
### (Fases / Subprojetos)

Sugere-se organizar o trabalho em **7 subprojetos**, com lógica incremental e progressiva:

1. Governança e Preparação Institucional  
2. Diagnóstico e Mapeamento do Acervo Físico  
3. Desenho do Processo SEI–SIPE (AS IS / TO BE)  
4. Benchmarking e Articulação Interinstitucional  
5. Digitalização do Acervo Físico (piloto + escala)  
6. Indexação no SIPE e Operação Assistida  
7. Aprimoramentos, Automação e Sustentação  

Essa abordagem evita iniciar a digitalização sem clareza de processo (“digitalizar no escuro”).

---

## 3. Plano de ação e cronograma  
### (Formato de tabela)

> **Observação importante**  
> As durações e prazos são **estimativas iniciais**, compatíveis com um projeto desse porte.  
> Ajustes mais precisos deverão ser realizados após a fase de diagnóstico.

> **Nota**  
> O detalhamento do plano de ação será apresentado em formato de tabela contendo, por exemplo:
> - Fase / Subprojeto  
> - Atividade  
> - Responsável  
> - Entregáveis  
> - Prazo estimado  
> - Dependências  

(Essa tabela pode ser incorporada em versão posterior do documento.)

---

## 4. Sugestões estratégicas e pontos de atenção

### 4.1 Comece pequeno (piloto bem escolhido)

Selecionar uma unidade com:
- Alto volume documental;
- Setor de RH estruturado;
- Boa interlocução local.

Um piloto bem conduzido reduz significativamente riscos em escala.

---

### 4.2 Separe claramente três dimensões do processo

Evitar confusão entre:

- Digitalização física dos documentos;
- Armazenamento e organização no SEI;
- Indexação e vinculação no SIPE.

Misturar essas etapas costuma gerar retrabalho e inconsistências.

---

### 4.3 Atenção ao identificador da Pasta Funcional

Na prática:
- O **Processo SEI** é o principal identificador da PFE.
- O SIPE complementa com:
  - CPF;
  - MASP;
  - Admissão;
  - Instituição.

Recomenda-se formalizar essa definição em **normativo interno**.

---

### 4.4 Automação (com pragmatismo)

- **API do SEI** possui potencial para:
  - Consulta de número de documentos;
  - Validação de classificação (020.5).
- O SIPE atualmente:
  - Possui forte dependência de ações manuais.
- A automação pode iniciar com:
  - RPA (preenchimento assistido);
  - Validações simples.

Recomenda-se tratar automação como **fase posterior**, e não como pré-requisito.

---

### 4.5 Governança e riscos

**Riscos críticos identificados**:
- Digitalização sem padrão;
- Indexação incorreta (admissão errada, pasta errada);
- Criação indevida de múltiplas PFEs.

**Medidas de mitigação**:
- Checklists padronizados;
- Dupla conferência no piloto;
- Auditoria amostral periódica.

---

## Considerações finais

Este documento estabelece uma base sólida para a implementação do processo de gestão documental funcional da FHEMIG, alinhado ao SEI e ao SIPE, respeitando a realidade institucional e permitindo evolução incremental e sustentável.

## Anotações GPT

Dica de uso inteligente PROJECTS (data de vencimento)

Depois, você pode criar uma view no Project:

Filtro:

due:<@today


mostra tarefas atrasadas

Ou:

due:<=@next-week


próximas da entrega

Isso é muito poderoso para gestão.


teste123