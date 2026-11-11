****DESAFIO TÉCNICO – HPC MONITOR****

Sistema de acompanhamento de processamento computacional

1. Sobre o projeto

Olá!

Trabalho em um laboratório de pesquisa onde realizamos diversos experimentos e cálculos computacionais que, em alguns casos, levam bastante tempo para serem concluídos.

Atualmente, temos dificuldade em acompanhar o que está acontecendo com esses processamentos. Muitas vezes precisamos acessar diretamente o ambiente computacional para verificar se uma execução ainda está acontecendo, se terminou ou se apresentou algum problema.

Gostaríamos de ter uma ferramenta que facilitasse esse acompanhamento, reunindo todas essas informações em um único lugar.

Não precisamos de algo extremamente complexo, mas queremos uma solução funcional, organizada e que possa ser expandida futuramente.

2. O que precisamos?

Gostaríamos de uma aplicação web onde fosse possível visualizar os processamentos realizados no nosso ambiente computacional.

Imagine que um pesquisador iniciou um processamento e gostaria de acompanhar:

- Quais processamentos estão acontecendo no momento.
- Quais já foram finalizados.
- Quais apresentaram algum erro.
- Quanto tempo cada processamento está levando.
- Quem iniciou cada processamento.
- Quando cada processamento começou e terminou.

Também gostaríamos de consultar o histórico dos processamentos anteriores.

3. Cadastro e gerenciamento

Precisamos que seja possível cadastrar e gerenciar os processamentos.

Cada processamento deverá ter algumas informações:

- Nome do processamento.
- Descrição.
- Responsável.
- Data e hora de início.
- Data e hora de término.
- Status atual.
- Informações sobre a máquina utilizada.

Também precisamos conseguir visualizar os detalhes, editar informações e excluir registros quando necessário.

4. Acompanhamento dos recursos computacionais

Outro ponto importante é conseguir visualizar como nossas máquinas estão trabalhando.

Gostaríamos de acompanhar algumas informações, como:

- Percentual de utilização do processador (CPU).
- Utilização da memória RAM.
- Espaço disponível em disco.
- Quantidade de processamentos em execução.

Seria interessante apresentar essas informações em gráficos e indicadores visuais, para facilitar o entendimento.

5. Notificações pelo Telegram ou Discord

Temos outra necessidade: nem sempre estamos olhando para a plataforma.

Por isso, gostaríamos de receber notificações por meio de um bot no Telegram ou Discord.

Por exemplo:

- Quando um processamento começar.
- Quando um processamento terminar.
- Quando um processamento apresentar erro.
- Quando a utilização de algum recurso estiver muito alta.

Também gostaríamos de conseguir consultar algumas informações pelo próprio chat.

Por exemplo, enviar uma mensagem para o bot e receber a lista de processamentos que estão acontecendo naquele momento.

6. Histórico e relatórios

Gostaríamos de conseguir consultar os processamentos realizados anteriormente, filtrando por período, responsável e status.

Também seria interessante conseguir exportar essas informações para um arquivo, para que possamos utilizá-las em relatórios internos.

7. O que esperamos da solução?

Queremos uma aplicação simples de utilizar, com uma interface intuitiva e que apresente as informações de maneira organizada.

Não temos uma tecnologia específica definida. Esperamos que você escolha as ferramentas que considerar mais adequadas para desenvolver a solução.

Também gostaríamos que o projeto fosse organizado de maneira que pudéssemos adicionar novas funcionalidades no futuro.

8. Entrega

Ao final do desenvolvimento, esperamos receber:

- A aplicação funcionando.
- O código-fonte versionado em um repositório Git.
- Instruções para instalação e execução.
- Documentação básica de utilização.
- Uma demonstração da aplicação.
- Demonstração da integração com o Telegram ou Discord.

9. Observação importante

Não esperamos que você desenvolva um sistema capaz de executar cálculos científicos complexos.

Nosso objetivo inicial é conseguir acompanhar e visualizar os processamentos e os recursos computacionais de maneira centralizada.

Você terá liberdade para propor melhorias e funcionalidades adicionais que considerar interessantes.
