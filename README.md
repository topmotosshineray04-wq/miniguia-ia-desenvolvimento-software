# 🤖 Caderno Temático — IA Aplicada ao Desenvolvimento de Software

> **Projeto prático desenvolvido para o Desafio de Projeto da Digital Innovation One (DIO)**  
> **Ferramenta Utilizada:** NotebookLM (Google)  
> **Tema:** Como a Inteligência Artificial pode atuar como assistente no ciclo completo de desenvolvimento de software  

---

## 📚 Sobre o Projeto

Este projeto consiste em um **Caderno Temático e Miniguia de Estudos** estruturado no **NotebookLM**, com o objetivo de explorar o uso da Inteligência Artificial Generativa como ferramenta de aprendizagem ativa e suporte técnico no ciclo de vida de desenvolvimento de software (SDLC).

Através da aliança entre **pensamento crítico, curadoria de fontes oficiais/acadêmicas e engenharia de prompts**, o projeto documenta desde a estruturação das perguntas até a identificação de limitações, alucinações e "cicatrizes" do processo de interação com a IA.

---

## 🎯 Objetivos de Estudo

1. **Compreender a aplicação prática da IA** nas etapas de levantamento de requisitos, arquitetura, codificação, testes, documentação e manutenção.
2. **Desenvolver habilidades de Engenharia de Prompts** (contextualização, delimitação de escopo e refinamento iterativo).
3. **Avaliar criticamente os riscos e limitações** (alucinações, segurança de código, privacidade, acoplamento e viés de automação).
4. **Criar um repositório de conhecimento reutilizável** (glossário, resumos e templates de prompts) para futuras revisões e projetos.

---

## 📖 Curadoria de Fontes

Para garantir rigor técnico e evitar respostas baseadas em conteúdos superficiais, foram selecionadas **5 fontes abertas de relevância global**:

| Fonte | Instituição / Autor | Título / Tema | Link de Acesso |
| :--- | :--- | :--- | :--- |
| **Fonte 1** | **Google Cloud** | *Executive Guide to Generative AI & Software Development* | [Acessar Documento](https://cloud.google.com/application/files/executive-guide-to-generative-ai.pdf) |
| **Fonte 2** | **Microsoft Security** | *Microsoft Responsible AI Standard, v2* | [Acessar Documento](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4V2gd) |
| **Fonte 3** | **IBM Research** | *AI for Software Engineering: AI-Powered Lifecycle* | [Acessar Documento](https://www.ibm.com/downloads/cas/QB2E2X8W) |
| **Fonte 4** | **NIST** | *Artificial Intelligence Risk Management Framework (AI RMF 1.0)* | [Acessar Documento](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf) |
| **Fonte 5** | **ACM / IEEE (ArXiv)** | *Generative AI in Software Engineering: A Systematic Mapping Study* | [Acessar Documento](https://arxiv.org/abs/2307.08177) |

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

### 📌 Evolução dos Prompts Testados

#### ❌ Prompt 01 (Genérico / Escopo Aberto)
> *"Explique como a Inteligência Artificial pode ser utilizada no desenvolvimento de software. Apresente benefícios, limitações e riscos com base nas fontes."*
* **Resultado:** Resposta muito genérica, sem separação por etapas do desenvolvimento, misturando conceitos avançados com básicos.
* **Problema:** Falta de estrutura e delimitadores claros.

#### ⚠️ Prompt 02 (Segmentado por Etapas)
> *"Com base nas fontes fornecidas, explique como a IA auxilia nas etapas: 1. Requisitos; 2. Arquitetura; 3. Programação; 4. Testes; 5. Manutenção. Apresente benefícios e riscos para cada etapa."*
* **Resultado:** Resposta significativamente melhor, porém omitiu a necessidade de validação humana e aspectos específicos de segurança do código.

#### ✅ Prompt 03 (Estratégico / Maturação Técnica)
> *"Atue como um Arquiteto de Software Sênior e Especialista em Segurança. Com base **exclusivamente** nas 5 fontes do notebook, elabore uma análise crítica detalhada sobre o uso de IA Generativa no SDLC. Para cada etapa (Requisitos, Arquitetura, Codificação, Testes, Manutenção), detalhe: (a) Casos de uso práticos; (b) Principais riscos de segurança e privacidade; (c) Estratégias de mitigação e necessidade de verificação humana. Adicione citação exata das fontes."*
* **Resultado:** Resposta extremamente rica, estruturada e diretamente aplicável a cenários reais de engenharia de software.

---

### 🩹 Cicatrizes do Processo (Troubleshooting)

1. **Alucinação / Generalização excessiva:**
   * *Ocorrência:* Em respostas iniciais, a IA sugeriu ferramentas que não constavam nas fontes.
   * *Solução:* Inclusão da instrução restritiva de ancoragem: *"Responda utilizando **exclusivamente** as informações contidas nos documentos carregados"*.
2. **Superficialidade nos aspectos de Segurança:**
   * *Ocorrência:* A IA focou apenas em produtividade e velocidade de escrita de código.
   * *Solução:* Alteração do *persona prompt* para *"Especialista em Segurança de Software e Governança de IA"*, o que forçou a citação do framework NIST AI RMF.

---

## 📘 Miniguia de Estudo & Entregas

* 📄 **[Resumo Estruturado dos Estudos](./estudos/resumo.md)**
* 📖 **[Glossário de Conceitos Key](./estudos/glossario.md)**
* 🛠️ **[Engenharia de Prompts Detalhada](./estudos/engenharia-de-prompts.md)**
* ♻️ **[Prompts Reutilizáveis](./prompts/prompts-reutilizaveis.md)**
* 📸 **[Evidências no NotebookLM](./evidencias/README.md)**

---

## 🏁 Conclusão

A utilização do **NotebookLM** alinhada às diretrizes da **DIO** demonstrou que a IA não deve ser vista como uma substituta do pensamento crítico do desenvolvedor, mas sim como um **parceiro cognitivo e copiloto de produtividade**. A verdadeira maturidade técnica reside na capacidade de **fazer as perguntas certas, checar as fontes e validar minuciosamente qualquer saída gerada por IA**.
