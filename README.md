# treinamento-web-basico

Projeto utilizado para o treinamento de nível básico em desenvolvimento web com Java e jQuery. O resultado final deve ficar igual ao projeto Qualify, utilizado como avaliação técnica dos conceitos apresentados nos treinametos.

## Estrutura de módulos:

* *Módulo 1* - Introdução ao desenvolvimento web:
  * Como baixar a aplicação do github
  * Como criar uma branch
  * Como rodar a aplicação
  * Apresentação da estrutura básica da aplicação
  * Demonstração do princípio básico de comunicação HTTP
    * Criação de um formulário no index da aplicação com 1 input, um span e um botão de submit.
    * Criação de um end-point que recebe uma string e retorna uma mensagem "Hello {string}".
    * Criação do evento que consome este endpoint via ajax através do botão de sumit do formulário contruido.
  * Como realizar commit and push no github
* *Módulo 2* - Introdução ao font-end:
  * Criação de um formulário para cadastro de carros
  * Estilização do formulário utilizando bootstrap
  * Implementação de validação para o formulário utilizando jQuery
  * Implementação de comportamento para o formulário utilizando jQuery
    * Caso o tipo do carro seja esporte mostrar um radio para escolher roda de liga ou ferro
  * Implementar submissão do formulário serializado e mostrar no console a saída JSON que será consumida depois no back  
  * Criação e estilização de uma listagem dinâmica gerada a partir de um objeto JSON
  * Criação de um mecanismo de navegação entre o formulário e a listagem
* *Módulo 3* - Orientação à objetos na prática: 
  * Criação das classes de objetos utilizadas para mapear o usuário cadastrado no formulário criado no módulo anterior
  * Explicação e demonstração sobre generalização, erança e polimorfismo sobre as classes anteriores
  * Criação de um end-point para receber a submissão do formulário, mapeada no objeto modelo de dados e imprimir no console
* *Módulo 4* - Banco de dados básico
  * Contrução das tabelas do domínio da aplicação (Carros, Marcas e Pessoas)
  * Insersão/Carga de dados iniciais nas tabelas via declarações sql (insert, update, delete)
  * Apresentação de conceitos de consultas avançadas (com parâmetros em joins e conceitos de indexação importantes para desempenho)
* *Módulo 5* - Conceitos básicos de ORM e camada de persistência
  * Mapeamento das classes modelo de objeto desenvolvidas no módulo 3 em entidades com a utilização das anotações do hibernate
  * Criação dos repositories
    * Explicar a implementação de um método básico de consulta e como ele funciona (como o sql é cirado pelo hibernate e executado)
    * Demonstrar a execução do método debugando e logando a query no console
    * Mostrar os métodos padrões herdados da interface de CRUD do spring (os métodos básicos de CRUD), abordar/explicar porque não é necessário declará-los, Demonstrar como podem ser sobrescritos/personalizados
* *Módulo 6* - Integrando o back-end e o front-end
  * Ajustar a listagem para consumir os carros do back-end 
  * Revisar o fluxo de inserção para
  * Criar os fluxos de edição e exclusão
