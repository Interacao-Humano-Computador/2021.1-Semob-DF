# Planejamento da Análise de Tarefas

## Versionamento

Data | Versão | Descrição | Autor(es) | Revisado por
---|---|---|---|---
10.09.2021 | 0.1 | Criação do documento | Arthur, Brenno e Eliás | 

## 1. Introdução
<div style="text-align: justify">A avaliação de IHC é fundamental para se obter um produto de qualidade de uso. Este tipo de processo orienta o avaliador a identificar problemas no sistema que possam prejudicar a experiência particular dos usuários.

O presente documento tem por finalidade apresentar o planejamento da avaliação, contendo as informações necessárias para o entendimento da mesma.
</div>

## 2. Metodologia Escolhida
A equipe optou por realizar o método percurso cognitivo, que consiste em avaliar a facilidade de aprendizado por exploração de um sistema. As tarefas dos usuários são decompostas em uma sequência de passos necessários para realizar a tarefa, e então o avaliador analisa cada ação tentando se colocar no lugar do usuário, procurando compreender se as tais ações conduzem a tarefa desejada. Caso encontre um problema, o avaliador propõe soluções (Baranauskas & Rocha, 2003; Silva & Barbosa, 2010; Nielsen & Mack, 1994 apud Preece et alii, 2005).

### 2.1. Preparação
<div style="text-align: justify">Durante a fase de preparação os avaliadores ficam responsáveis pela definição dos objetos, que consistem nas tarefas a serem analisadas e os passos necessários em cada tarefa de estudos, sendo que as tarefas a serem utilizadas devem ter sido identificadas previamente em algum tipo de análise de tarefas, e do material de apoio, que deve estar definido as perguntas do método e o perfil dos usuários utilizados para a avaliação.</div> 
<div style="text-align: justify">Como preparação de nosso projeto iremos utilizar como base as tarefas de <i>Pesquisa por linhas de transporte</i>, <i>Pesquisa de pontos de referencia</i>, e <i>Consulta de leis</i> definidas na <a href="https://interacao-humano-computador.github.io/2021.1-Semob-DF/#/pages/analiseDeTarefa">Árvore de Tarefas Concorrentes</a>, além do próprio site do <a href="https://semob.df.gov.br/">SEMOB</a>.</div>

#### Tarefa 1 - Pesquisa por linhas de transporte
<div style="text-align: justify"><b>Perfil do usuário:</b> Pessoa que deseja pesquisar ônibus por locais de referência<br>
<b>Passos:</b><br>
1. Acessar o site do SEMOB<br>
2. Acessar link "DF no Ponto - Horários e itinerários dos ônibus"<br>
3. Acessar a aba "Linha"<br>
4. Inserir número da linha<br>
5. Acessar linha</div>

#### Tarefa 2: Pesquisa de pontos de referência
<div style="text-align: justify"><b>Perfil do usuário:</b> Pessoa que deseja pesquisar por uma linha específica<br>
<b>Passos:</b><br>
1. Acessar o site do SEMOB<br>
2. Acessar link "DF no Ponto - Horários e itinerários dos ônibus"<br>
3. Acessar a aba "Referência"<br>
4. Inserir origem<br>
5. Inserir destino<br>
6. Acessar linhas condizentes</div>

#### Tarefa 3: Consultar leis
<div style="text-align: justify"><b>Perfil do usuário:</b> Pessoa que deseja consultar alguma lei<br>
<b>Passos:</b><br>
1. Acessar o site do SEMOB<br>
2. Encontrar aba "Leis e Regulamentações"<br>
3. Acessar o ano desejado<br>
4. Acessar a lei desejada</div>

### 2.2. Coleta de Dados
<div style="text-align: justify">O avaliador, ao desenvolver a fase da coleta de dados, deve simular os passos definidos em cada tarefa, verificando o "se" e o "por que" de um usuário navegar de forma a alcançar seu objetivo, além de utilizar as perguntas do método para auxiliar na identificação de problemas.</div><br>
<div style="text-align: justify">Como exemplo retirado do livro <i>Interação Humano-Computador e Experiência do usuário</i> as perguntas devem ser analisadas:<br>
<b>P1:</b> <i>O usuário tentaria atingir o efeito correto? A formulação da intenção do usuário seria a esperada (pelo designer do sistema)?</i><br>
"Um usuário tem mais chance de formular a intenção correta se: a ação faz parte da tarefa tal como concebida pelo usuário; o usuário tem experiência em utilizar o sistema avaliado ou sistemas semelhantes; ou o sistema fornece uma instrução ou solicita que o usuário realize a ação;"(BARBOSA et al., 2021)<br>
<b>P2:</b> <i>O usuário perceberia que a ação correta está disponível?</i><br> 
"Um usuário normalmente sabe que uma ação está disponível se: tem experiência em utilizar o sistema avaliado ou sistemas semelhantes; ou se percebe na interface uma representação da ação desejada (por exemplo, em um item de menu, link ou botão de comando);"(BARBOSA et al., 2021)<br>
<b>P3:</b> <i>O usuário conseguiria associar a ação correta com o efeito que está tentando atingir?</i><br> 
"O usuário costuma saber qual ação é adequada para o efeito esperado se: tem experiência em utilizar o sistema avaliado ou sistemas semelhantes; se a interface comunica essa associação entre a ação e o efeito esperado; ou se nenhuma outra ação parece adequada (i.e., por eliminação);"(BARBOSA et al., 2021)<br>
<b>P4:</b> <i>Se a ação correta for realizada, o usuário perceberia que está progredindo para concluir a tarefa?</i><br> 
"O usuário geralmente sabe que está avançando na direção da conclusão da tarefa se: tem experiência em utilizar o sistema avaliado ou sistemas semelhantes; ou as respostas do sistema estão de acordo com o efeito esperado."(BARBOSA et al., 2021)<br>
</div>

### 2.3. Interpretação e Consolidação dos Resultados
Para interpretarmos os resultados, precisamos responder algumas fundamentais...
<h3>O que o usuário precisa saber a priori para realizar as tarefas ?</h3>
<p>Primeiramente para o usuário ser capaz de realizar as 3 tarefas ele precisa ter um conhecimento prévio em computação básica, como acessar a internet e acessar o site SEMOB, ter em mente alguma linha que deseja procurar e/ou o local de chegada e destino.
</br>
</br>
<h3>o que o usuário deve aprender enquanto realiza as tarefas ?</h3>
<p>O usuário deve aprender finalizar as tarefas com conhecimento de transportes públicos que fazem a rota que ela deseja, também espera-se que ele saiba a respeito das leis e as regulamentações a respeito do transporte publico</p>

<h3>sugestões de correções para os problemas encontrados ?</h3>
<p>O usuário deve aprender finalizar as tarefas com conhecimento de transportes públicos que fazem a rota que ela deseja, também espera-se que ele saiba a respeito das leis e as regulamentações a respeito do transporte publico</p> 

### 2.4. Relato dos Resultados
gerar um relatório consolidado com os problemas encontrados e sugestões de
correção
## 3. Referência
BARBOSA, Simone; SILVA, Bruno; SILVEIRA, Milene; GASPARINNI, Isabela; DARIN, Ticiane; BARBOSA, Gabriel. <b>Interação Humano-Computador e Experiência do usuário.</b>[S. l.]: Autopublicação, 2021.

ROCHA, Heloísa Vieira Da;  BARANAUSKAS, Maria Cecília Calani. Design e Avaliação de Interfaces Humano-Computado.  Campinas: Unicamp, 2003.

PREECE, Jennifer;  ROGERS, Yvonne;  SHARP, Helen. Design de Interação: Além da Interação Humano-Computador. Porto Alegre: Bookman, 2005.