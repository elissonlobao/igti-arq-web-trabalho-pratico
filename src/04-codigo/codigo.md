# O nível 4: O código
O projeto ***CrDigital*** irá englobar todos os requisitos funcionais e não funcionais exigidos para uma aplicação que envolve premissas como citados usabilidade, disponibilidade, desempenho, confiabilidade e segurança.
A escolha pelo um modelo Frontend e Backend pelo fato da sua configuração permitir que o sistema seja construído de forma separada, podendo tais atividades serem realizadas, também, por equipes diferentes. Ela permite uma melhor modularidade das fronteira, facilitando a evolução e até mesmo a substituição de tecnologias sem grandes impactos. 

Será utilizado o framework ***Angular*** para a construção dos módulos de front-end da Aplicação WEB e para a Aplicação SPA por ser  um framework baseado em javascript utilizado para a construção de aplicações web robustas. Seus vários recursos proporcionando um resultado na usabilidade com excelente qualidade de leiaute, navegabilidade com um controle forte pelos seus  componentes que garantem confiabilidade e segurança. Permite uma melhor apresentação de responsividade da Aplicação Front-end e possui todos os recursos necessários para implementar os serviços das integrações com alto desempenho e disponibilidade através de seus módulos e diretivas injetadas:

![angular-architecture](https://angular.io/generated/images/guide/architecture/overview2.png  "Arquitetura do Angular")


Para a construção do Aplicativo Mobile, foi eleio o ***Xamarin***. O Xamarin é uma plataforma de software livre para a criação de aplicativos modernos e de alto desempenho para os principais Sistemas Operacionais Mobile (iOS e Android). Ele incorpora uma camada de abstração que gerencia a comunicação de código compartilhado com o código de plataforma subjacente e é executado de maneira gerenciada, fornecendo controle de alocação de memória e coleta de lixo. Sua arquitetura provê que e os aplicativos sejam criados e reconhecidos nativos dos Sistemas Operacionais:

![xamarin-architecture](https://docs.microsoft.com/pt-br/xamarin/get-started/what-is-xamarin-images/xamarin-architecture.png  "Arquitetura do Xamarin")


Como solução robusta para a API Back-end, será utilizado a plataforma ***Java EE***. O Java EE é um ambiente para desenvolvimento de aplicações corporativas de grande porte e aplicações web que possui bibliotecas e funcionalidades que implementam softwares baseados na linguagem Java. Ela oferece recursos que atendem a todos os requisitos funcionais e não funcionais da solução e proporciona uma efetiva integração entre os containers e componentes:

![xamarin-architecture](https://i1.wp.com/readlearncode.com/wp-content/uploads/2017/02/java_ee_8_apis.png  "Arquitetura do Xamarin")


Foi definido um Banco de Dados relacional para o gerenciamento e armazenamento das informações a partir de um mapeamento Objeto Relacional ORM para reduzir a impedância da programação orientada aos **objetos**.
O Banco de dados eleito foi o ***Oracle*** por possuir uma arquitetura considerada flexível e rica em recursos para otimização de performance. Sua integração com o JPA do Java EE proporciona integridade transacional com alta disponibilidade, performance e cache, simplificando o gerenciamento, reduzindo o tempo e esforços exigidos em atualizações, backups e manutenções.