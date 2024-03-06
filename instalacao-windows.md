## Instalação no Windows

#### 1 - Download dos binários
Para realizar a instalação do Elasticsearch e do Kibana primeiro é necessário fazer o download dos binários na versão Windows no site oficial da Elastic.
Elastisearch: https://www.elastic.co/pt/downloads/elasticsearch

![](https://github.com/jcampolim/ElasticGuide/blob/main/img/download-elasticsearch.png)

Kibana: https://www.elastic.co/pt/downloads/kibana

![](https://github.com/jcampolim/ElasticGuide/blob/main/img/download-kibana.png)

#### 2 - Extrair binário do Elasticsearch
Extraia o binário do Elasticsearch.

#### 3 - Executar binário do Elasticsearch
Execute o binário através do Windows PowerShell. Dentro do diretório do Elasticsearch execute o comando: `.\bin\elasticsearch.bat`.

![](https://github.com/jcampolim/ElasticGuide/blob/main/img/elasticBat.jpg)

#### 4 - Salvar informações
No final da instalação do Elasticsearch haverá uma mensagem de segurança com várias informações importantes, entre elas a senha gerada para o usuário interno elastic e o token para a habilitação e configuração do Kibana. Copie essas informações e as salve no bloco de notas para acessá-las posteriormente posteriormente.

![](https://github.com/jcampolim/ElasticGuide/blob/main/img/elasticInfo.jpg)

** O token para o Kibana é válido por apenas 30 minutos, caso ele tenha exipirado até o momento da configuração do Kibana, é necessário gerar outro token.

#### 5 - Extrair binário do Kibana
Extrair o binário do Kibana.

#### 6 - Executar binário do Kibana
Execute o binário do Kibana em outra janela do PowerShell (não feche a janela do Power Shell com o Elasticsearch em execução). Dentro do diretório do Kibana execute o comando: `.\bin\kibana.bat`.

![](https://github.com/jcampolim/ElasticGuide/blob/main/img/kibanaBat.jpg)

#### 7 - Abrir o link do Kibana
No final da instalação do Kibana, clique no link que aparece no output de instalação. Esse link direciona ao localhost do Kibana, onde o processo de instalação será finalizado.

![](https://github.com/jcampolim/ElasticGuide/blob/main/img/kibanaOutput.jpg)
![](https://github.com/jcampolim/ElasticGuide/blob/main/img/kibanaLink.jpg)

#### 8 - Integração do Kibana com o Elasticsearch
Copie o token presente na mensagem final do output de instalação do Elasticsearch e colar no espaço correspondente do browser. 

![](https://github.com/jcampolim/ElasticGuide/blob/main/img/blocoToken.jpg)
![](https://github.com/jcampolim/ElasticGuide/blob/main/img/kibanaToken.jpg)

Após isso, automaticamente o kibana faz a integração com o Elasticsearch (que está em execução em outra janela do PowerShell), deixando o ambiente pronto e seguro.

![](https://github.com/jcampolim/ElasticGuide/blob/main/img/elasticConfigure.jpg)

#### 9 - Login no Kibana
A última etapa é na tela de login do Kibana, que pede o nome de usuário e a senha do usuário interno gerado pelo Elasticsearch.

![](https://github.com/jcampolim/ElasticGuide/blob/main/img/login.jpg)

Pronto! O Elasticsearch e o Kibana estão configurados e integrados dentro da máquina. Para conseguir acessá-los é preciso executar os binários dos dois e abrir o localhost do Kibana (`localhost5601`).