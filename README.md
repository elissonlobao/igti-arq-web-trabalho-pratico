# CrDigital

Como solução para a necessidade, o ***CrDigital*** que será composto por um Portal de serviços e por um aplicativo que abrangerá todos os serviços necessários para o efetivo atendimento das necessidades dos clientes da cooperativa.
Foi escolhido um modelo Frontend e Backend em camadas que simplifica a implementação e evolução, não comprometendo os requisitos não funcionais de usabilidade, disponibilidade, desempenho, confiabilidade e segurança. 
>Os requisitos não funcionais são detalhados no item [código](#código).
# visão arquitetural
A arquitetura do sistema foi documentada utilizando o modelo C4 de arquitetura por considerar as estruturas estáticas de um sistema de software por um conjunto comum de abstrações distribuídos em termos de contexto, containers, componentes e código de forma a fornecer diferentes níveis de abstração, cada um dos quais com relevância específica.

Níveis de abstração:
* [01 - Diagrama de contexto](#diagrama-de-contexto)
* [02 - Diagrama de container](#diagrama-de-container)
* [03 - Diagrama de componentes](#diagrama-de-componentes)
* [04 - Código](#código)

## 01 - Diagrama de contexto
O Diagrama de contexto do sistema tem por finalidade demonstrar como estará distribuídos as conexões com o meio exterior (Usuários, Serviços e Integrações), e como ele interage com esse meio. A visão desta abstração está representada pelo diagrama abaixo:

![Diagrama de contexto](https://github.com/elissonlobao/igti-arq-web-trabalho-pratico/blob/main/docs/01-diagrama-contexto/01-diagrama_contexto.svg "Diagrama de contexto")

## 02 - Diagrama de container
O diagrama de container surge a partir de uma ampliação do container do sistema de software no diagrama de  contexto e exibe por uma visão de hosts o que compõem esse sistema de software com um detalhamento das tecnologias eletivas que fundamentam a arquitetura proposta, sendo detalhada abaixo: 

![Diagrama de contexto](https://github.com/elissonlobao/igti-arq-web-trabalho-pratico/blob/main/docs/02-diagrama-de-container/02-diagrama-de-container.svg "Diagrama de container")

O diagrama é composto de cinco containers: uma aplicação de página única do lado do cliente, uma aplicação móvel, uma aplicação Web Front-end, uma aplicação em API Back-end e um banco de dados.

## 03 - Diagrama de componentes
Integração 
Releases de baixo risco

## 04 - Código
, bem como de, manutenção e tecnologias envolvidas