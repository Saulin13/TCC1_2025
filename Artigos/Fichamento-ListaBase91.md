# Using Large Language Models to Generate Concise and Understandable Test Case Summaries

Djajadi, Natanael; Deljouyi, Amirhossein; Zaidman, Andy. "Using Large Language Models to Generate Concise and Understandable Test Case Summaries." ICPC 2025 (ERA).

## 1. Fichamento de Conteúdo

O trabalho investiga se LLMs podem gerar resumos de casos de teste mais concisos e compreensíveis do que abordagens baseadas em templates (TestDescriber, DeepTC‑Enhancer). Os autores comparam diferentes técnicas de prompting (baseline simples, engineering, awareness de contexto e few‑shot) e três modelos (CodeLlama 7b, GPT‑3.5 e GPT‑4o). Em um estudo com 11 participantes, resumos gerados por LLMs foram preferidos, sobretudo em concisão e naturalidade, enquanto CodeLlama com prompt engineering se destacou em conteúdo e GPT‑4o (few‑shot) em concisão. A solução foi integrada ao UTGen, com pacote de replicação.

## 2. Fichamento Bibliográfico

* Test summarization: gerar uma descrição curta do que o teste cobre (classe/método alvo, condição verificada).
* Prompt engineering: estrutura do prompt (passos, persona, exemplos) para melhorar completude e clareza do resumo.
* Modelos avaliados: CodeLlama 7b (open‑source), GPT‑3.5 e GPT‑4o (comerciais).
* Ferramentas baseline: TestDescriber e DeepTC‑Enhancer (templates).
* UTGen: integração prática para incorporar os resumos na geração/gestão de testes.


## 3. Fichamento de Citações

* _"we investigate whether large language models (LLMs) can be used to generate more concise, yet understandable summaries."_
* _"In a small-scale user study with 11 participants, we obtained positive feedback on the LLM-generated summaries."_
* _"LLM-generated summaries outperformed template-based ones in naturalness."_