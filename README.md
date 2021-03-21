<img src="https://mark-tucker.gallerycdn.vsassets.io/extensions/mark-tucker/aws-cli-configure/0.3.0/1528734149540/Microsoft.VisualStudio.Services.Icons.Default" alt="AWS CLI logo" title="AWS CLI " align="right" height="128" width="128"/>

# Computação em Nuvem - Construindo API REST com AWS

## Assuntos Envolvidos
- Desenvolvimento de uma API para cadastro de clientes.
- Linguagem utilizada JavaScript + NodeJS.
- Arquitetura Serveless utilizando recursos AWS.
- AWS Lambda Function para construção da lógica da aplicação.
- Como expor a API no AWS API Gateway.
- Configurar um banco de dados AWS DynamoDB.
- Segregar os ambientes de DEV, QA e PROD.
- Realizar o deploy da aplicação para AWS.

## Requisitos
- Conhecimento em alguma linguagem de programação.

## Ferramentas utilizadas
- [AWS CLI versão 2](https://aws.amazon.com/pt/cli/)
A Interface da Linha de Comando (ILC) da AWS é uma ferramenta unificada para o gerenciamento de seus serviços da AWS. 
Com apenas uma ferramenta para fazer download e configurar, você 
poderá controlar vários serviços da AWS pela linha de comando e automatizá-los usando scripts.
#
- [Serverless Framework](https://www.serverless.com) 
O serverless framework é uma ferramenta muito útil que simplifica 
muito o trabalho de construir aplicações serverless, ele possui um universo 
extenso de plugins que estendem as capacidades desta ferramenta.
#
-  [Markdown-Editor ](https://jbt.github.io/markdown-editor/).
Ferramenta muito bacana e online para a vizualização do README.md em tempo de execução

## Trilha

-  [Baixar o instalador AWS CLI V2](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/install-windows.html).
- Fazer a instalação e configuração do AWS CLI
- Criar uma conta de serviço no console da AWS
- Fazer a instalação e configuração do Serverless Framework
- Criar uma função na AWS Lambda
- Visualizar logs no AWS CloudWatch
- Para exemplificação do projeto: após clonar o projeto do GIT e criar as devidas contas no AWS digite o comando abaixo...
```
sls deploy
```
O proprio Serverless Framework fará  o deploy e retornará com as URLs para teste ^^


