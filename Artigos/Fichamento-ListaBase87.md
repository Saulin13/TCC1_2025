# Automated Refactoring of Non-Idiomatic Python Code: A Differentiated Replication with LLMs

Midolo, Alessandro; Di Penta, Massimiliano. "Automated Refactoring of Non-Idiomatic Python Code: A Differentiated Replication with LLMs." arXiv, 2025. arXiv:2501.17024.

## 1. Fichamento de Conteúdo

O artigo replica e amplia estudos de refatoração idiomática em Python, agora explorando o uso de LLMs (como GPT-4) para identificar e sugerir transformações de código que aproximem trechos “não-pythônicos” de construções idiomáticas. Os autores comparam as recomendações do LLM com uma abordagem de linha de base baseada em análise estática e transformações programáticas. O estudo indica que o LLM identifica oportunidades adicionais e, em amostras auditadas manualmente, produz sugestões corretas com frequência. A pesquisa discute os limites (p.ex., casos de borda e consistência) e fornece pacote de replicação. o estudo demonstra que modelos generativos podem complementar (ou substituir parcialmente) heurísticas e regras de refatoração, reduzindo esforço de manutenção, elevando legibilidade e, potencialmente, eficiência do código, embora exija validação humana e testes automatizados.

## 2. Fichamento Bibliográfico

* Refatoração idiomática ("Pythonic idioms"): converter código para construções idiomáticas que aumentam legibilidade e concisão (p.ex., compreensões, desempacotamento).
* LLM (GPT-4): modelo de linguagem usado para recomendar ações de refatoração a partir do contexto do código.
* Análise estática e transformação de código: baseline tradicional para detectar e aplicar refatorações programáticas.
* Pacote de replicação: scripts/dados que permitem reproduzir o experimento e avaliar sugestões em novos repositórios.


## 3. Fichamento de Citações

* _"GPT-4 not only identifies idiomatic constructs effectively but frequently exceeds the benchmark"_
* _"Our findings underscore the potential of LLMs to achieve tasks where complex code analyses was required."_
* _"there is room for enhancement in handling edge cases."_