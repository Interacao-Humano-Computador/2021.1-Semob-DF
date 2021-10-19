### Versionamento
Data | Versão | Descrição | Autor(es) | Revisado por
 -- | -- | -- | -- | --
 03/09/2021 | 0.1 | Criação do documento | Ana Júlia | Laís Portela
 03/09/2021 | 0.2 | Criação dos subtopicos e explicação da expectativa do usuário| Laís Portela | Ana Júlia
 03/09/2021 | 0.3 | Realização dos subtópicos: Simplicidade nas estruturas das tarefas e Equilíbrio entre controle e liberdade do usuário| Ana Júlia | Laís Portela
03/09/2021 | 0.4 | Realização dos subtópicos: Consistência e Padronização, Promovendo a Eficiência do Usuário e Antecipação. Introdução e Conclusão| Laís Portela | Ana Júlia
03/09/2021 | 0.5 | Realização dos subtópicos: Visibilidade e Reconhecimento, Conteúdo Relevante Expressação Adequada e Projeto para Erros. Referências| Ana Júlia | Lívia Rodrigues
18.08.2021 | 0.6 | Padronização do nome do versionamento | Lais Portela

## Introdução
Foram feitos princípios e diretrizes que nos mostram como projetar um sistema que atenda as necessidades do usuário, para que ele possa aprender e utilizar os sistemas de modo rápido e prático. Norman destaca a necessidade de projetar o sistema utilizando o modelo conceitual, que deve auxiliar a interpretar o relacionamento entre as ações e informações apresentadas pelo sistema e o conhecimento no mundo.

O designer auxilia o usuário a ter a melhor experiência possível, então seguindo esses princípios e diretrizes o design poderá ser projetado de modo a ter um sistema útil e prático a quem o utilizar.

## Principios e Diretrizes Gerais

### Correspondências com a expectativa do usuário
Em relação ao produto o usuário tem uma expectativa, que pode ser boa ou ruim. 

Em sistemas digitais a ordem das ações do usuário precisa ser o mais parecido com o do mundo físico. Como no exemplo da imagem abaixo, uma pessoa ao ir a uma loja comprar uma roupa, por exemplo, ela não se identifica com os seus dados pessoais antes de poder escolher o produto. Assim tem que ser ao comprar a roupa em um site também, primeiro você olha o catálogo e após a escolha que faz o login para finalizar a compra. Segundo Norman isso é <b>explorar os mapeamentos naturais.</b>

<img width="487px" height="156px" src="images/sequenciaIdentificacaoUsuario.png">

Um feedback é ideal para informar o usuário que a ação dele foi concluída.

Além de se preocupar com a parte estrutural é necessário, também preocupar-se com o aspecto do designer, utilizando palavras familiares. Também é recomendado o uso de metáforas de forma cuidadosa, segundo Tognazzini, para permitir que o usuário identifique rapidamente sutilezas do modelo conceitual subjacente ao sistema.


### Simplicidade nas Estruturas das Tarefas
De acordo com Norman, tarefas desnecessariamente complexas podem ser reestruturadas de modo a facilitar o entendimento dela. Ele recomenda simplificar a estrutura das tarefas, reduzindo a quantidade de planejamento e resolução de problemas que eles requerem.

### Equilíbrio entre Controle e Liberdade do Usuário
É sempre bom lembrar que o usuário está no controle, a ele "pertence" o computador, a interface e o ambiente de trabalho. Mas isso requer um equilíbrio, pois dando muita liberdade ao usuário pode fazer com que ele se sinta perdido ou angustiado com o excesso de opções. Norman, recomenda explorar o poder das restrições, tanto naturais como artificias.

O software deve ter "jogo de cintura", ser maleável, permitir que o usuário saia a qualquer momento ou cancele determinada ação, porém, a opção mais fácil deve ser se manter no caminho. Ter a possibilidade de errar diminui a ansiedade e o medo de errar do usuário, pois eles sabem que os erros podem ser desfeitos.

Entretanto, usar muitas caixas de diálogos para confirmação aumenta o tempo de realização das tarefas e pode fazer com que a comunicação seja ineficiente, pois muitos usuários acabam ficando sem paciência e só pulam os diálogos sem ler antes. Por isso a importância dos valores padrões (default), assim não precisamos incomodar o usuário quando não for necessário.

Devemos sempre manter um equilíbrio entre o que é oferecido ao usuário e a sua capacidade de entender as consequências da combinação de parâmetros escolhida.

### Consistência e Padronização

É recomendado que para facilitar o aprendizado e o uso do sistema, a interface deve ser consistente e padronizada.
Norman e Togbazzini acreditavam que a consistência mais importante é com as expectativas dos usuários. É recomendado por eles padronizar as ações, os resultados delas, o layout dos diálogos, e as visualizações de informação. 

Não pode haver dúvida do usuário se as palavras em situações diferentes significam a mesma coisa. O uso do botão Gravar e Salvar feito de modo indiscriminado por confundir quem usa o sistema.

Outro ponto a ter atenção é se funções diferentes tem aparências diferentes, por exemplo, apagar e salvar, se estiverem muito próximos, o usuário pode selecionar apagar ao invés de salvar e assim perder todo o seu trabalho. Para evitar tal infortúnio é preciso que o sistema tenha também mensagens de aviso para o usuário confirmar se deseja fazer a ação.


### Promovendo a Eficiência do Usuário
A eficiência do usuário deve ser considerada sempre em primeiro lugar, como pensar na economia de tempo e esforço do usuário. Fazer o usuário esperar a ação de um sistema ser concluída pode significar perde de produtividade e dinheiro, então para evitar isso, os processos demorados devem permitir que o usuário possa fazer outras coisas enquanto esperam.

O sistema deve ser sensível ao que o usuário faz, não mandando mensagens e avisos quando ele estiver ocupado em uma reunião, por exemplo. O sistema deve proteger o trabalho dos usuários, salvando automaticamente, em caso de perde de rede e outros problemas.

O sistema também deve manter-se informado sobre o usuário, permitindo, por exemplo, saber a última ação dele, para quando uma sessão nova for iniciada o sistema mostre exatamente onde o usuário estava e o que estava fazendo. 
Atalhos e aceleradores devem ser fornecidos ao usuário para possibilitar um trabalho mais ágil. Por fim, também é importante salvar as configurações selecionadas frequentemente pelo usuário, assim ele não perde tempo em fazer as mesmas ações novamente.

### Antecipação
Prever o que o usuário quer e precisa, por exemplo, ao colar uma imagem no editor de documentos, seria interessante ao sistema já mostrar opções de edição disponíveis, como cortar, editar saturação, entre outros. Assim o software toma a iniciativa e fornece informações úteis ao usuário.

A antecipação do software é estar sempre preparado a atender não somente ao usuário quer nesse momento, mas no que ele pode vir a querer. Para fazer isso o sistema pode observar e anotar as ações frequentes do usuário, para assim, tentar antever cada passo dele.

Tognazzi destaca a importância de definir de maneira cuidadosa os valores e configuração padrão(defaults). Substituições mais adequadas a situação atual, campos pré-selecionados. As pessoas aceitam essas configurações pré-estabelecidas pois não entendem o que se deve fazer, ou porque assumem que o sistema já aprendeu o que o usuário quer, por isso é necessário ter cuidado ao escolher os defaults.

### Visibilidade e Reconhecimento

Antes de uma ação ser executada, deve ser visível para o usuário o que é possível realizar e como as ações devem ser feitas. A interface deve estar ligada ao usuário de forma a saber quais intenções ele tem, quais ações ela deve oferecer, quais opções não oferecer. Norman afirma que o designer deve tornar as coisas visíveis: abreviar os golfos de execução e avaliação.

O estado do sistema deve estar sempre atualizado e facilmente perceptível, ele também deve manter o usuário informado sobre o que ocorreu ou que está ocorrendo, através do feedback. A resposta deve ser sutil, exceto em ações pouco frequentes e que acarretam grandes consequências, nessas situações a resposta deve ser mais substancial.

O usuário não deve ser responsável por fazer um mapa mental do que fez ou por onde passou no sistema. Em geral, as informações de status podem ser bem sutis.

### Conteúdo Relevante e Expressão Adequada

As Expressões utilizadas no sistema devem ser concisas e informativas sobre os problemas que ocorrerem, de modo a ajudar e facilitar as tarefas do usuário. Da mesma forma, os botões, menus e rótulos também devem ser claros e livres de ambiguidade, para não confundir o usuário. Deve se ter em mente que o usuário provavelmente vai fazer exatamente aquilo que o desenvolvedor pensou que não poderia ser feito, ele vai entrar justamente na aba que tem bugs, na aba que ele não deveria acessar, por isso é de extrema importância que os textos sejam legíveis e as instruções claras.

### Projeto para Erros

Como foi dito antes, dar a possibilidade de errar para o usuário deixa ele mais seguro, tira o medo e a angústia dele de utilizar o sistema. Por esse motivo, reverter as operações deve ser fácil, e realizar ações irreversíveis devem ser difíceis. Fazer o usuário perceber, reconhecer e diagnosticar onde errou, se recuperar dos erros e saber como revertê-los dá uma sensação de segurança necessária ao usuário. Ações que podem levar ao erro devem ser pouco utilizadas, assim como não se deve colocar funções muito utilizadas perto de controles perigosos ou que raramente são utilizados.

## Conclusão

A relação do usuário com o sistema deve ser bem coordenada. O sistema tem de ter ações intuitivas e fáceis como no mundo real, deve prevenir falhas que podem acarretar a perda do trabalho, sejam elas causadas pelo sistema, pelo meio externo ou pelo próprio usuário. 

O sistema nunca deve ser uma dor de cabeça a quem o utiliza, e manter padrões ajuda nisso, assim como dar liberdade ao usuário para escolher outras saídas, e também para poder continuar ser produtivo enquanto uma ação que exige tempo para a conclusão acontece.

Seguir estes princípios ajuda o sistema ser simples, prático e útil a quem o utiliza, o que eleva a expectativa do usuário de modo positivo.

### Referências Bibliográficas

Livro: Barbosa, S.D.J.; Silva, B.S.; Silveira, M.S.; Gasparini, I.; Darin, T.; Barbosa, G.D.J. (2021) Interação Humano-Computador e Experiência do Usuário.