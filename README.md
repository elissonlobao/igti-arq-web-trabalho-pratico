# Problema

A cooperMedice é umas das maiores cooperativas no ramo de planos de saúde que opera em todo Brasil, com mais de 5 milhões de clientes.
Atualmente ela está com dificuldades em atender sua demanda de serviços frente a nova realidade de mercado impulsionada pelo atual momento de pandemia da sociedade.

# Solução
A publicação de um novo website e um novo aplicativo para smartphones para proporcionar aos clientes as seguintes funcionalidades:

**APP:**
 - Carteirinha Digital
 - Consultas agendadas
 - Agendamento de consultas
 - Reembolso digital (upload de foto dos recibos) e dados do médico, valores etc
 - Código de barras para pagamento
 - Faturas
 - Valor da última fatura em aberto e o status
 - Catálogo de cooperados (Médicos).

**Website**
- Institucional.
- Propagandas dos Planos.
- Vendas de Planos.
- Todas as funcionalidades do APP.

Para atender a necessidade, foi inciado o projeto ***CrDigital*** para englobar todos os requisitos citados.
# CrDigital
Como solução para a necessidade, o ***CrDigital*** que será composto por um Portal de serviços e por um aplicativo que abrangerá todos os serviços necessários para o efetivo atendimento das necessidades dos clientes da cooperativa.

Foi escolhido um modelo Frontend e Backend em camadas que simplifica a implementação e evolução, não comprometendo os requisitos não funcionais de usabilidade, disponibilidade, desempenho, confiabilidade e segurança.

>Os requisitos não funcionais são detalhados no item [código](https://github.com/elissonlobao/igti-arq-web-trabalho-pratico/blob/main/docs/04-codigo/HOME.md).

# Visão arquitetural
Por se tratar de um projeto Ágil, a arquitetura do sistema foi documentada utilizando o modelo C4 de arquitetura. Este modelo considera as estruturas estáticas de um sistema de software por um conjunto comum de abstrações distribuídos em termos de contexto, containers, componentes e código de forma a fornecer diferentes níveis de abstração, cada um dos quais com relevância específica.

Níveis de abstração apresentados:

*  [01 - Diagrama de contexto](#diagrama-de-contexto)
*  [02 - Diagrama de container](#diagrama-de-container)
*  [03 - Diagrama de componentes](#diagrama-de-componentes)
*  [04 - Código](#código)
 

## Diagrama de contexto

O Diagrama de contexto do sistema tem por finalidade demonstrar como estará distribuídos as conexões com o meio exterior (Usuários, Serviços e Integrações) e como ele interage com esse meio. A visão desta abstração está representada pelo diagrama abaixo:

![Diagrama de contexto](https://github.com/elissonlobao/igti-arq-web-trabalho-pratico/blob/main/docs/01-diagrama-contexto/01-diagrama_contexto.svg  "Diagrama de contexto")

## Diagrama de container
O diagrama de container surge a partir de uma ampliação do container do sistema de software no diagrama de contexto e exibe por uma visão de hosts o que compõem esse sistema de software com um detalhamento das tecnologias eletivas que fundamentam a arquitetura proposta, sendo detalhada abaixo:

![Diagrama de container](https://github.com/elissonlobao/igti-arq-web-trabalho-pratico/blob/main/docs/02-diagrama-de-container/02-diagrama-de-container.svg  "Diagrama de container")

O diagrama é composto de cinco containers: uma aplicação de página única do lado do cliente, uma aplicação móvel, uma aplicação Web Front-end, uma aplicação em API Back-end e um banco de dados.

## Diagrama de componentes
O diagrama de componentes fornece um detalhamento a partir da ampliação de um container individual, visando mostrar os componentes que os compõe. Esses componentes demonstram um mapeamento real das abstrações da base de código. Descreve-se abaixo os componentes dentro da API da aplicação:

![Diagrama de componentes](https://github.com/elissonlobao/igti-arq-web-trabalho-pratico/blob/main/docs/03-diagrama-de-componentes/03-diagrama-de-componentes.svg  "Diagrama de componentes")
  

## Código
Neste nível de detalhamento, é demonstrado como o componente de pagamento é implementado, exibindo os elementos de código que o compõem:
  
O Front-end está demonstrado abaixo em uma visão detalhada para entendimento do que foi abstraído mais adiante:
  
![Diagrama de componentes](https://github.com/elissonlobao/igti-arq-web-trabalho-pratico/blob/main/docs/04-codigo/01-front-end.svg  "Front-end")
  
No diagrama de sequência abaixo, têm-se a demonstração completa do processo de geração de fatura de pagamento:

![Diagrama de componentes](https://github.com/elissonlobao/igti-arq-web-trabalho-pratico/blob/main/docs/04-codigo/02-diagrama-sequencia.svg  "Front-end")

>Os requisitos não funcionais são detalhados no item [código](https://github.com/elissonlobao/igti-arq-web-trabalho-pratico/blob/main/docs/04-codigo/HOME.md).