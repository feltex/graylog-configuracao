# Configuração do Graylog com Docker Compose

Bem-vindo ao repositório do projeto de configuração do Graylog utilizando Docker Compose. Este projeto foi criado com o objetivo de ensinar como configurar e executar o Graylog, uma poderosa ferramenta de gestão e análise de logs, de forma simples e eficiente utilizando contêineres Docker.

## Assista o nosso vídeo no youtube

https://youtu.be/yatpJUJy0nU



## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Configuração](#configuração)
- [Uso](#uso)

## Sobre o Projeto

O Graylog é uma solução open-source para coleta, indexação e análise de logs em tempo real. Este repositório contém um conjunto de arquivos de configuração do Docker Compose que automatizam o processo de implantação do Graylog e seus componentes necessários, como MongoDB e Elasticsearch.

## Pré-requisitos

Antes de começar, você precisará ter o seguinte instalado em sua máquina:

- Docker
- Docker Compose

## Instalação

Para começar a usar o projeto, siga os passos abaixo:

1. Clone este repositório para sua máquina local:

   ```bash
   git clone git@github.com:feltex/graylog-configuracao.git
   cd graylog-configuracao

## Configuração

 Após iniciar os contêineres, você pode acessar a interface web do Graylog através do endereço http://localhost:9000. Utilize as credenciais padrão configuradas no arquivo docker-compose.yml para fazer login.

Usuário: admin
Senha: admin (ou a senha que você configurou no arquivo de ambiente)

## Uso
Com o Graylog em execução, você pode começar a configurar entradas de log, criar streams, definir alertas e dashboards personalizados. 
Consulte a documentação oficial do Graylog para obter mais detalhes sobre como utilizar a ferramenta.   
