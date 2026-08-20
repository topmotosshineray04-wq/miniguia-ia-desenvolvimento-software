# 📘 Resumo Estruturado: IA no Ciclo de Desenvolvimento de Software (SDLC)

## 1. Introdução
A integração da IA Generativa no SDLC transforma a IA em um **copiloto cognitivo**.

## 2. Aplicação da IA nas Etapas do SDLC

### 2.1 Levantamento de Requisitos
* **Uso:** Clarificação de estórias de usuário e cenários BDD/Gherkin.
* **Benefício:** Redução de ambiguidades.
* **Risco:** Requisitos alucinados.

### 2.2 Arquitetura e Modelagem
* **Uso:** Sugestão de Design Patterns e esquemas SQL/PostgreSQL.
* **Benefício:** Aceleração do prototipamento.
* **Risco:** Arquiteturas obsoletas ou superdimensionadas.

### 2.3 Implementação e Codificação
* **Uso:** Autocompletar, geração de código legível e conversão de linguagens.
* **Benefício:** Ganho de velocidade em tarefas repetitivas.
* **Risco:** Injeção de falhas de segurança (OWASP) ou licenças violadas.

### 2.4 Testes e QA
* **Uso:** Testes unitários, mocks e análise de cobertura.
* **Benefício:** Cobertura de código otimizada.
* **Risco:** Testes falsos-positivos.

### 2.5 Documentação e Manutenção
* **Uso:** Criação de README, docstrings e explicações de código legado.
* **Benefício:** Documentação sempre atualizada.
* **Risco:** Informações imprecisas sobre funções críticas.

## 3. Boas Práticas e Governança
1. **Human-in-the-Loop:** Validação humana obrigatória em todo código/documento gerado.
2. **Sanitização:** Nunca enviar credenciais ou dados sensíveis em prompts.
3. **CI/CD:** Rodar linters e testes automatizados antes do merge.
