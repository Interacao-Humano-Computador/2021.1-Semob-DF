# Árvore de tarefas concorrentes (CTT)

## Versionamento

Data | Versão | Descrição | Autor(es)
---|---|---|---
26/08/2021 | 1.0 | Criação do documento | Brenno e Eliás

## 1. Introdução
Uma análise de tarefa é realizada para que se saiba a respeito do trabalho dos usuários, como realizam e porque realizam. Uma das técnicas de análise de tarefas é a **árvore de tarefas concorrentes (CTT)**, que tem por finalidade auxiliar a avaliação e o design e a avaliação de IHC. Neste modelo, existem 4 tipos de tarefas:
- Tarefas do usuário: realizada fora do sistema.
- Tarefas do sistema: processamentos do sistema que não possuem interação com o usuário.
- Tarefas interativas: ocorrem diálogos do tipo usuário-sistema.
- Tarefas abstratas: que não são tarefas em si, mas sim uma representação de uma composição de tarefas que auxilie a decomposição.

## 2. Nomenclaturas utilizadas

