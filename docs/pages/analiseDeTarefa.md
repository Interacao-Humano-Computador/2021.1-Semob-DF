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

<img src="images/CTT.png">

## 2. Nomenclaturas utilizadas
Este modelo (CTT) possue 8 possíveis interações entre as tarefas, são elas:
- **Ativação (T1 >> T2):** a segunda tarefa (T2) só pode iniciar se a primeira (T1) terminar.
- **Ativação com passagem de informação (T1 [] >> T2):** a segunda tarefa só pode ser iniciada após a primeira terminar, e as informações geradas em T1 deve ser passadas para T2.
- **Escolhas (T1 [] T2):** apenas uma será selecionada, e a restante será desativada.
- **Tarefas concorrentes (T1 ||| T2):** as tarefas podem ser realizadas em qualquer ordem ou ao mesmo tempo.
- **Tarefas concorrentes e comunicantes (T1 |[]| T2):** Além de poderem ser realizadas em qualquer ordem e ao mesmo tempo, podem trocar informações entre si.
- **Tarefas independentes (T1 |= |T2):** realizadas em qualquer ordem, mas apenas uma por vez.
- **Desativação (T1 [> T2):** T1 é completamente interrompida por T2.
- **Suspensão/retomada (T1 |> T2):** T1 pode ser interrompida por T2 e é retomada do ponto em que parou assim que T2 finalizar.

## 3. Resultados
### 3.1 Pesquisa por linhas de transporte

<img width="605px" height="620px" src="images/tarefa_4.png">

### 3.2 Pesquisa de pontos de referencia

<img width="525px" height="686px" src="images/Tarefa_5.png">



## 4. Referências bibliográficas
[1]Barbosa, S. D. J.; Silva, B. S. da. **Interação Humano-Computador e Experiência do usuário.** Rio de Janeiro: Elsevier, 2010.