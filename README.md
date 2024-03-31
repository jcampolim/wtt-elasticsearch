# Elasticsearch

Link da apresentação: [elasticsearch](https://www.canva.com/design/DAF98d0QWLw/yBZT-1eTN4StuwFhUPXkHA/edit?utm_content=DAF98d0QWLw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Sumário

* Elastic Stack
  * Elasticsearch
  * Logstash
  * Kibana

* Download
* Acesso web

## Elastic stack

O Elastic Stack, também conhecido por ELK Stack, é um conjunto de ferramentas de software open source projetado para facilitar a coleta de dados em grande escala. Ele é amplamente usado para a análise de logs, monitoramento de sistemas, segurança da informação e visualização de dados.

É composto por quatro componentes principais: Elasticsearch, Kibana, Logstash e Beats (neste documento falaremos apenas dos três primeiros).

![](https://github.com/jcampolim/wtt-elasticsearch/blob/main/img/elastic-stack.png)

O Elastic é uma ferramenta flexível e personalizável para atender às necessidades especifícas de diferentes cenários, sendo uma escolha popular para projetos com grandes volumes de dados.

#### 1 - Elasticsearch

O Elasticsearch é um mecanismo de busca distribuído e de código aberto, projetado para armazenar, buscar e analisar grandes volumes de dados em tempo real e de maneira eficiente. Funciona como um banco de dados não relacional. Ele faz parte do Elastic Stack, sendo fundamental para a indexação e recuperação eficiente de informações em conjuntos de dados distribuídos. 

O Elasticsearch é particularmente utilizado em casos de uso como pesquisa textual, análise de logs, monitoramento de sistemas e análise de dados, oferecendo escalabilidade, flexibilidade e uma poderosa capacidade de pesquisa e indexação. É comumente empregado em ambientes empresariais para facilitar a busca e análise de dados em larga escala.

![](https://github.com/jcampolim/wtt-elasticsearch/blob/main/img/elasticsearch-api.png)

#### 2 - Logstash

O Logstash é uma ferramento de processamento de dados de código aberto, cuja principal função é facilitar a coleta, transformação e envio de dados de diversas fontes para serem armazenados. Pode se conectar a diversos serviços, sendo altamente flexível.

O Logstash é utilizado em ambientes onde a coleta e processamento de dados de diferentes fontes são essenciais, como análise de logs, monitoramento de sistemas e ingestão de dados para análise em tempo real. Seu uso é popular para a integração em pipelines de dados complexos.

![](https://github.com/jcampolim/wtt-elasticsearch/blob/main/img/logstash.png)

#### 3 - Kibana

O Kibana é uma interface gráfica de código aberto que pode se conectar com qualquer aplicação (banco de dados, API ou servidor). Sua função é facilitar a visualização, exploração e interpretação dos dados armazenados na aplicação, permitindo a criação de dashboard iterativos e gráficos personalizados.

É amplamente usado em cenários onde a análise visual de dados é essencial, como o monitoramento de sistemas, análise de logs, métricas de desempenho e investigação de eventos em tempo real.

![](https://github.com/jcampolim/wtt-elasticsearch/blob/main/img/kibana-1.jpeg)

![](https://github.com/jcampolim/wtt-elasticsearch/blob/main/img/kibana-3.jpg)

## Download

É possível utilizar as ferramentas apresentadas fazendo o download de cada uma e seguindo o passo a passo para a instalação do Elasticsearch e do Kibana: [instalacao-windows](https://github.com/jcampolim/wtt-elasticsearch/blob/main/instalacao-windows.md).

* Elasticsearch: https://www.elastic.co/pt/downloads/elasticsearch

* Kibana: https://www.elastic.co/pt/downloads/kibana

* Logstash: https://www.elastic.co/pt/downloads/logstash

Também é possível usar o Elastic Stack pelo site [](elastic.co), porém ao se cadastrar você tem acesso há apenas 15 dias grátis.
