# Batalha de dados - Suporte
Este repositório tem o intuito de disponibilizar conteúdos para apoiar no evento Batalha de Dados.

# Materiais de apoio:

Materiais de apoio referente aos serviços a conceitos e serviços AWS.

- [Conceitos básicos da AWS](https://aws.amazon.com/pt/getting-started/?nc2=h_ql_le_gs)
- [Cloud Computing na AWS](https://aws.amazon.com/pt/what-is-aws/?nc1=h_ls)
    [O que é computação em nuvem](https://www.youtube.com/watch?v=OFIVUTmc2cs)

- [Bons exemplos de "QuickStart"](https://aws.amazon.com/pt/quickstart)


# Configurar aws-cli

A AWS Command Line Interface (AWS CLI) é uma ferramenta de código aberto que permite interagir com os serviços da AWS usando comandos no shell da linha de comando. Com o mínimo de configuração, a AWS CLI permite iniciar a execução de comandos que implementam uma funcionalidade equivalente à fornecida pelo Console de gerenciamento da AWS baseado em navegador no prompt de comando em seu programa de terminal.

Utilizaremos o AWS cli para configurar os templates das nossas stacks.

[Como configurar o aws-cli](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-chap-welcome.html)

# Como Baixar os dados ?

- Configure AWS Cli conforme o item anterior com a access key e secret key que voce recebeu do time organizador.

- Rode o seguinte comando: `aws s3 cp s3://batalhasocial-iu . --recursive`

Voce pode também utilizar alguma SDK de sua preferencia pra fazer a utilização dos dados.

[Boto3 para Python](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/s3-example-download-file.html)

[Como configurar o Boto?](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/quickstart.html#configuration)
# CloudFormation Templates

O AWS CloudFormation é um serviço que ajuda você a modelar e configurar seus recursos da Amazon Web Services para despender menos tempo gerenciando esses recursos e mais tempo se concentrando em seus aplicativos executados AWS.

Os recursos são disponiveis para provisionamento utilizando Cloud Formation, esses templates são previamente configurados para provisionar os recursos em sua conta AWS de forma mais simples e pronta para utilização no Hackathon.

[CloudFormation Templates](AWS%20-%20Support/cloudformation)

# Vídeos de apoio

Nesta sessão você encontrara vídeos para te auxiliar na construção do seu projeto no Hackathon.

[Videos](AWS%20-%20Support/videos)
