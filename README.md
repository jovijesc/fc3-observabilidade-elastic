# Projeto de Estudo com Elastic Stack

O objetivo deste projeto é apresentar um exemplo prático de implementação de observabilidade utilizando a Elastic Stack, com foco no módulo de Observabilidade do curso Full Cycle 3.0. 
<br/>Os serviços utilizados são:

- Elasticsearch
- Kibana
- Metricbeat
- Heartbeat
- APM

***

## Passos iniciais

Para executar este projeto, siga os passos abaixo:

1. Execute o docker compose da Elastic Stack na raiz do projeto:

    ```docker-compose up -d```


2. Acesse a pasta `app` e execute o seguinte comando:

    ```docker-compose up -d --build```


3. Acesse a URL do Kibana em seu navegador: http://localhost:5601/


***
<br/>

## Elastic Stack

A Elastic Stack é uma suíte de software de código aberto que inclui diversas ferramentas para coleta, análise e visualização de dados. A seguir, uma breve explicação de cada uma das ferramentas da Elastic Stack:

- **Elasticsearch**: é um mecanismo de busca e análise distribuído e de código aberto, usado para armazenar, pesquisar e analisar grandes volumes de dados. Ele é altamente escalável e pode ser usado para uma variedade de casos de uso, como pesquisa fulltext, análise de logs e métricas, entre outros.

- **Kibana**: é uma interface web que permite visualizar e interagir com os dados armazenados no Elasticsearch. Ele fornece recursos de visualização de dados, como gráficos e tabelas, além de permitir que os usuários criem dashboards personalizados e relatórios.

- **Metricbeat**: é um agente de coleta de métricas que coleta e envia métricas de sistemas para o Elasticsearch ou para outros destinos. Ele suporta uma grande variedade de módulos para coleta de métricas, incluindo infraestrutura, sistema operacional, contêineres, bancos de dados, cloud etc.

- **Heartbeat**: é um agente de monitoramento que verifica a disponibilidade de serviços, sites e servidores. Ele é usado para garantir que os aplicativos estejam funcionando corretamente e para alertar os usuários quando ocorrerem falhas ou interrupções.

- **APM (Application Performance Monitoring)**: é um conjunto de ferramentas que permite monitorar o desempenho e a disponibilidade de aplicativos em tempo real. Ele fornece informações detalhadas sobre o desempenho dos aplicativos, incluindo tempos de resposta, erros e transações. Ele também pode ser usado para rastrear erros e diagnosticar problemas de desempenho.
