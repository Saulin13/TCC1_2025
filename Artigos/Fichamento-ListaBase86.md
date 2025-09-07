# Leveraging multi-task learning to improve the detection of SATD and vulnerability

Russo, Barbara; Melegati, Jorge; Mock, Moritz. "Leveraging multi-task learning to improve the detection of SATD and vulnerability." arXiv, 2025. arXiv:2501.15934.

## 1. Fichamento de Conteúdo

O artigo avalia se aprendizado multi‑tarefa (MTL) pode melhorar a detecção automática de dívida técnica auto‑admitida (SATD) e vulnerabilidades em código. Os autores propõem o modelo VulSATD, baseado em CodeBERT, e constroem o MADE‑WIC ao fundir anotações de funções com rótulos de vulnerabilidade e SATD. Comparando abordagens single‑task e multi‑task (com loss ponderada), não foram observadas diferenças significativas de desempenho. A interpretação é que apenas um subconjunto de SATD pode estar associado a aspectos de segurança.

## 2. Fichamento Bibliográfico

* SATD (Self‑Admitted Technical Debt): comentários/código que reconhecem compromissos técnicos assumidos temporariamente.
* Aprendizado multi‑tarefa (MTL): treinar uma rede para aprender tarefas relacionadas compartilhando representações.
* CodeBERT: modelo pré‑treinado para código usado como backbone.
* MADE‑WIC: conjunto de dados fundido com rótulos de vulnerabilidade e SATD.
* Métrica: comparação entre single‑task e multi‑task com função de perda ponderada.


## 3. Fichamento de Citações

* _"we implemented VulSATD, a deep learner that detects vulnerable and SATD code based on CodeBERT"_
* _"obtaining no significant differences even after employing a weighted loss."_
* _"the relationship between different types of technical debt and software vulnerabilities deserves future exploration"_