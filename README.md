# Desafio DIO — GenAI, Dados e Cibersegurança

## 1. Sobre o Projeto

Este projeto apresenta uma investigação conceitual sobre a relação entre **Inteligência Artificial Generativa (GenAI), Large Language Models (LLMs), dados e cibersegurança**, considerando possíveis aplicações em ambientes bancários orientados por dados.

A investigação foi conduzida a partir de fontes técnicas e institucionais disponibilizadas no NotebookLM, buscando compreender:

* conceitos de cibersegurança e gestão de riscos;
* riscos relacionados a aplicações baseadas em LLMs;
* gestão de riscos associados à Inteligência Artificial Generativa;
* possíveis relações entre esses domínios;
* lacunas que permanecem quando esses conceitos são considerados em conjunto no contexto bancário.

O projeto não apresenta uma solução tecnológica bancária existente. A proposta é documentar o processo de investigação, diferenciando **evidências encontradas nas fontes, inferências resultantes da comparação e hipóteses que ainda precisam ser investigadas**.

---

## 2. Problema Investigado

Ambientes bancários dependem de dados, sistemas digitais e mecanismos de segurança para suportar operações críticas.

Ao mesmo tempo, a utilização crescente de GenAI e LLMs introduz novos riscos e questões relacionadas à segurança, governança, confiabilidade e gerenciamento de riscos.

A questão central investigada neste projeto é:

> **Como os conceitos de cibersegurança, gestão de riscos de IA, segurança de LLMs e dados podem ser analisados de forma integrada em um ambiente bancário orientado por dados?**

A investigação não parte da premissa de que exista uma solução pronta. Em vez disso, procura identificar quais elementos são sustentados pelas fontes e quais relações ainda representam hipóteses de pesquisa.

---

## 3. Objetivo

Investigar, de forma estruturada, como diferentes referências de cibersegurança e gerenciamento de riscos de IA podem contribuir para a compreensão de um ambiente que envolva:

**Cibersegurança + Gestão de Riscos de IA + Segurança de LLMs + Dados**

O objetivo também é identificar:

* pontos de convergência entre os frameworks;
* aspectos complementares;
* possíveis capacidades resultantes da combinação dos conceitos;
* lacunas relacionadas a dados, IA e segurança;
* questões que exigiriam fontes adicionais ou investigação futura.

---

## 4. Fontes de Referência

As análises foram realizadas utilizando os seguintes documentos principais disponíveis no NotebookLM.

### NIST Cybersecurity Framework (CSF) 2.0

**Pascoe, C.; Quinn, S.; Scarfone, K. (2024).**

O NIST CSF 2.0 fornece uma taxonomia de resultados de alto nível para auxiliar organizações a compreender, avaliar, priorizar e comunicar seus esforços de cibersegurança.

A fonte destaca, entre outros elementos:

* cybersecurity risk governance;
* cybersecurity risk management;
* enterprise risk management;
* Profiles;
* Tiers;
* aplicabilidade a organizações de diferentes setores, tamanhos e níveis de maturidade.

A fonte também estabelece que o CSF não prescreve como os resultados devem ser alcançados.

**Fonte oficial:**
https://www.nist.gov/cyberframework

---

### OWASP Top 10 for LLM Applications 2025

Fonte dedicada aos riscos de segurança associados a aplicações que utilizam Large Language Models.

O material utilizado na investigação contextualiza a expansão dos LLMs em diferentes setores e aplicações, incluindo interações com clientes e operações internas, além da evolução das vulnerabilidades e das abordagens de segurança relacionadas a essas aplicações.

**Fonte oficial:**
https://genai.owasp.org/llm-top-10/

---

### NIST AI Risk Management Framework / Generative AI Profile

**NIST AI 600-1 — Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile (2024).**

O documento é apresentado como um perfil complementar ao AI RMF para Inteligência Artificial Generativa.

A fonte aborda:

* gerenciamento de riscos de IA;
* trustworthiness;
* design, desenvolvimento, uso e avaliação de sistemas de IA;
* ciclo de vida de IA;
* atores envolvidos em IA;
* riscos específicos associados à GenAI;
* ações de gerenciamento de riscos alinhadas aos objetivos e prioridades das organizações.

**Fonte oficial:**
https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence

---

## 5. Abordagem de Investigação

A investigação foi conduzida por meio de perguntas estruturadas no NotebookLM.

As respostas foram analisadas considerando três níveis:

### Evidência

Informação diretamente sustentada pelo conteúdo das fontes utilizadas.

### Inferência

Relação ou interpretação construída a partir da comparação entre conceitos presentes nas fontes.

### Hipótese

Possibilidade de pesquisa que não é respondida diretamente pelas fontes e que necessita de investigação adicional.

Essa diferenciação foi adotada para evitar apresentar interpretações ou possibilidades arquiteturais como se fossem fatos estabelecidos pelas referências.

---

## 6. Principais Relações Identificadas

### 6.1 Cibersegurança e Gestão de Riscos

O NIST CSF 2.0 apresenta a cibersegurança dentro de uma perspectiva de gerenciamento de riscos, incluindo governança, gestão de riscos corporativos, Profiles e Tiers.

**Classificação:** Evidência direta.

---

### 6.2 Segurança de LLMs

O OWASP Top 10 for LLM Applications 2025 aborda riscos associados à utilização de LLMs em aplicações e operações, destacando a evolução das vulnerabilidades relacionadas a esse tipo de tecnologia.

**Classificação:** Evidência direta.

---

### 6.3 Gestão de Riscos de IA Generativa

O NIST AI RMF e o Generative AI Profile fornecem uma abordagem específica para gerenciamento dos riscos relacionados à IA, incluindo considerações de confiabilidade e aspectos do ciclo de vida dos sistemas de IA.

**Classificação:** Evidência direta.

---

### 6.4 Governança como ponto de convergência

Os documentos analisados apresentam diferentes perspectivas sobre governança e gerenciamento de riscos.

O NIST CSF 2.0 trata da governança de riscos de cibersegurança; o NIST AI RMF estrutura o gerenciamento de riscos de IA; e o material do OWASP trata dos desafios de segurança associados às aplicações baseadas em LLMs.

**Classificação:** Inferência resultante da comparação.

A existência de diferentes abordagens de governança nas fontes permite investigar como esses domínios poderiam ser relacionados, mas as fontes não prescrevem uma estrutura única de governança integrada.

---

## 7. Hipótese de Pesquisa

A partir da comparação das fontes, foi formulada a seguinte hipótese:

> **Seria possível conceber uma camada de inteligência para ambientes bancários que conecte sinais de dados, riscos de cibersegurança e capacidades de GenAI/LLMs, utilizando governança e gestão de riscos como mecanismos de controle?**

A hipótese **não é apresentada como uma solução existente**.

As fontes fornecem fundamentos relacionados individualmente a cibersegurança, riscos de IA e segurança de LLMs. A conexão desses elementos em uma camada de inteligência constitui uma hipótese derivada da investigação.

**Classificação:** Hipótese de pesquisa.

---

## 8. Exemplos de Investigação / Respostas Obtidas

### Investigação 1 — Governança e risco

**Pergunta:**
Quais conceitos do NIST CSF 2.0 poderiam ser relevantes para um ambiente bancário orientado por dados?

**Resultado:**
A análise identificou governança de riscos de cibersegurança, gerenciamento de riscos corporativos, Profiles, Tiers e uma taxonomia de resultados de alto nível como conceitos relevantes.

**Classificação:** Evidência da fonte.

A aplicação específica desses conceitos ao ambiente bancário constitui interpretação contextual.

---

### Investigação 2 — Segurança de LLMs

**Pergunta:**
Quais questões de segurança surgem quando LLMs são incorporados a aplicações e operações?

**Resultado:**
O OWASP evidencia a existência de riscos e vulnerabilidades específicas associados à utilização de LLMs em aplicações, incluindo cenários envolvendo operações internas e interações com clientes.

**Classificação:** Evidência da fonte.

---

### Investigação 3 — Integração dos domínios

**Pergunta:**
As fontes permitem investigar uma possível integração entre cibersegurança, gestão de riscos de IA e segurança de LLMs?

**Resultado:**
Sim. Os documentos apresentam conceitos relacionados a esses diferentes domínios. Entretanto, nenhum dos documentos analisados descreve uma arquitetura única que os integre em uma camada de inteligência bancária.

**Classificação:** Inferência → Hipótese de pesquisa.

---

### Investigação 4 — Dados

**Pergunta:**
As fontes respondem integralmente como proteger dados bancários durante todo o ciclo de utilização de LLMs?

**Resultado:**
Não. As fontes fornecem fundamentos relacionados a cibersegurança, privacidade, riscos de IA e segurança de aplicações, mas não respondem integralmente às questões específicas de um ambiente bancário envolvendo ciclo de vida de dados, RAG, treinamento, inferência, linhagem de dados e exposição a serviços de terceiros.

**Classificação:** Lacuna identificada.

---

## 9. Capacidades Investigadas

A comparação das fontes permitiu identificar algumas capacidades que podem ser investigadas, sem tratá-las como componentes de uma solução já existente.

| Capacidade                                           | Classificação                                 |
| ---------------------------------------------------- | --------------------------------------------- |
| Governança de riscos                                 | Evidência direta                              |
| Identificação e gestão de riscos de IA               | Evidência direta                              |
| Identificação de riscos específicos de LLMs          | Evidência direta                              |
| Avaliação de confiabilidade de sistemas de IA        | Evidência direta                              |
| Monitoramento e avaliação de riscos                  | Evidência / interpretação conforme o contexto |
| Correlação de informações entre diferentes domínios  | Inferência das fontes                         |
| Rastreabilidade integrada de dados e decisões        | Hipótese / lacuna                             |
| Resposta coordenada entre cibersegurança e IA        | Inferência / hipótese                         |
| Utilização de IA como mecanismo de defesa integrado  | Hipótese de pesquisa                          |
| Controle de agentes autônomos em operações bancárias | Hipótese de pesquisa                          |

A classificação busca evitar que uma capacidade inferida da combinação dos frameworks seja apresentada como uma funcionalidade explicitamente prescrita por eles.

---

## 10. Lacunas Identificadas

A investigação também revelou questões que não são suficientemente respondidas pelas fontes analisadas.

### Dados sensíveis

As referências abordam segurança, privacidade e riscos de IA, mas não fornecem uma especificação completa de controles para dados bancários sensíveis.

### Ciclo de vida dos dados

O NIST AI RMF considera o ciclo de vida dos sistemas de IA, mas isso não equivale a uma especificação completa do ciclo de vida de dados bancários.

### RAG

O OWASP Top 10 for LLM Applications 2025 aborda riscos relacionados a vetores, embeddings e arquiteturas que utilizam mecanismos de recuperação de informação. Entretanto, as referências utilizadas nesta investigação não constituem, isoladamente, uma especificação completa para todos os requisitos de segurança, governança e proteção de dados de uma arquitetura RAG em ambiente bancário.

### Treinamento e inferência

As fontes fornecem uma visão de gerenciamento de riscos de IA e de aplicações de LLM, mas não constituem, isoladamente, uma especificação completa de segurança para todas as etapas de treinamento e inferência em ambientes bancários.

### Rastreabilidade

A necessidade de avaliação, governança e gerenciamento de riscos é sustentada pelas fontes. Entretanto, a implementação de uma linhagem técnica completa conectando dados, modelos, entradas, saídas e decisões permanece como questão de investigação.

### Serviços de terceiros

A utilização de LLMs em aplicações cria questões relacionadas ao gerenciamento de riscos e segurança. Porém, os documentos analisados não fornecem, isoladamente, todos os requisitos regulatórios e técnicos necessários para avaliar a exposição de dados bancários a provedores externos.

---

## 11. Questões para Investigação Futura

A partir das lacunas identificadas, algumas questões permanecem abertas:

1. Como mapear os resultados de cibersegurança do NIST CSF 2.0 para requisitos específicos do setor bancário?
2. Como integrar gerenciamento de riscos de IA ao gerenciamento de riscos de cibersegurança?
3. Como garantir rastreabilidade de dados utilizados por aplicações baseadas em LLM?
4. Como tratar dados sensíveis durante treinamento, inferência e recuperação de informações?
5. Como avaliar riscos relacionados à utilização de modelos e serviços de terceiros?
6. Como testar sistemas de IA de forma contínua em ambientes críticos?
7. Como equilibrar autonomia de sistemas de IA com governança, controle e rastreabilidade?
8. Quais mecanismos seriam necessários para que uma eventual camada de inteligência pudesse correlacionar informações provenientes de diferentes domínios?

Essas questões representam **direções de investigação**, não funcionalidades já implementadas.

---

## 12. Limitações da Investigação

Esta investigação possui algumas limitações deliberadas:

* as conclusões são condicionadas às fontes disponibilizadas no NotebookLM;
* os frameworks possuem diferentes objetivos e níveis de abstração;
* o NIST CSF 2.0 não prescreve como seus resultados devem ser alcançados;
* o NIST AI RMF / Generative AI Profile possui caráter transversal e não é específico para instituições bancárias;
* o OWASP concentra-se na segurança de aplicações baseadas em LLMs;
* a combinação dos frameworks apresentada neste projeto é uma interpretação investigativa e não uma integração oficialmente estabelecida entre os documentos;
* questões regulatórias, jurídicas e operacionais específicas do setor bancário exigem fontes adicionais.

---

## 13. Projeto Relacionado

Como continuidade dos estudos realizados neste desafio, existe um **projeto relacionado em desenvolvimento** dedicado ao aprofundamento dos temas de GenAI, dados e cibersegurança em contexto bancário.

O projeto relacionado não faz parte da entrega deste desafio e permanece em desenvolvimento.

A relação entre os projetos é conceitual:

**Desafio DIO → investigação e fundamentação**

**Projeto relacionado → aprofundamento técnico em desenvolvimento**

---

## 14. Estrutura da Documentação

A documentação deste projeto foi organizada para registrar a investigação realizada, suas fontes, relações identificadas, hipóteses, lacunas e questões para investigação futura.

A estrutura poderá evoluir conforme novas etapas de estudo sejam realizadas.

---

## 15. Status

**Status:** Investigação e desenvolvimento.

O projeto encontra-se em evolução, com documentação das análises realizadas, hipóteses identificadas, lacunas e questões para investigação futura.

Os elementos ainda não validados permanecem explicitamente classificados como hipóteses, lacunas ou questões de investigação.

---

## 16. Conclusão

A análise das fontes demonstra que **cibersegurança, gerenciamento de riscos de IA e segurança de aplicações baseadas em LLMs possuem pontos de contato relevantes**, especialmente nos temas de governança, gerenciamento de riscos, avaliação e segurança.

Entretanto, a existência desses pontos de contato não significa que os frameworks apresentem uma solução integrada para ambientes bancários.

A principal contribuição desta investigação é justamente separar:

**o que as fontes afirmam → o que pode ser inferido → o que ainda precisa ser investigado.**

A hipótese de uma **camada de inteligência capaz de relacionar dados, cibersegurança, riscos de IA e capacidades de GenAI/LLMs** permanece, portanto, como uma linha de investigação.

O aprofundamento dessa hipótese exige fontes adicionais, experimentação controlada e validação técnica e regulatória.

---

## Referências

* **NIST Cybersecurity Framework (CSF) 2.0** — National Institute of Standards and Technology, 2024.
  https://www.nist.gov/cyberframework

* **OWASP Top 10 for LLM Applications 2025** — OWASP.
  https://genai.owasp.org/llm-top-10/

* **Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile (NIST AI 600-1)** — National Institute of Standards and Technology, 2024.
  https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence
