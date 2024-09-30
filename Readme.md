# **_Curso: Oferecido pela Cousera | Princípios técnicos da nuvem AWS_** <br/>

## **Laboratório 1: Introdução ao AWS Identity and Access Management**

## 👩🏼‍💻 **Conhecimentos adquiridos neste laboratório:**

✅Explorar usuários e grupos do IAM 

✅Inspecionar políticas do IAM aplicadas a grupos

✅Seguir um cenário real que adiciona usuários a grupos e explora permissões de grupo

✅Localizar e usar o URL de login do IAM

✅Experimentar políticas e acesso a serviços


## 👩🏼‍💻 **Visão geral do Laboratório:**


✅Três usuários: user-1, user-2 e user-3

✅Três grupos: com as seguintes políticas:

1 - Suporte do S3: acesso Read-Only(Somente leitura) ao Amazon Simple Storage Service (Amazon S3).

2 - Suporte do EC2: acesso Read-Only (Somente leitura) ao Amazon Elastic Compute Cloud (Amazon EC2).

3 - Administrador do EC2: disponibilidade para View (Visualizar), Start (Iniciar) e Stop (Interromper) instâncias do EC2.


## 👩🏼‍💻 **Execução do laboratório:**


✅Verifiquei os usuários, grupos e politicas do IAM ;

✅Gerenciei os usuários e grupos;

✅Adicionei o user-1 ao grupo s3-support;

✅Adicionei o user-2 ao grupo ec2-support;

✅Adicionei o user-3 ao grupo ec2-admin;

✅Fiz uma analise nas atribuições de usuários e grupos;

✅Acessei a URL de login do IAM;

✅Fiz login com o user-1;

✅Fiz testes no nível de acesso do user-1;

✅Fiz login com o user-2;

✅Fiz testes no nível de acesso do user-2;

✅Fiz login com o user-3;

✅Fiz testes no nível de acesso do user-3.

✅Finalizado o Laboratório.

## **Segue algumas capturas de tela desse Laboratório:**

![Laboratorio1](https://github.com/paolacsouza/curso-aws/blob/main/lab1/grupo_de_usuario.jfif)

![Laboratorio1](https://github.com/paolacsouza/curso-aws/blob/main/lab1/usuarios.jfif)

![Laboratorio1](https://github.com/paolacsouza/curso-aws/blob/main/lab1/login_iam.jfif)

![Laboratorio1](https://github.com/paolacsouza/curso-aws/blob/main/lab1/interrupcao_da_instancia.jfif)


## **_____________________________________________________________________________________________________**

## **Laboratório 2: Criar uma VPC e iniciar um aplicativo web na instância do Amazon EC2**

## 👩🏼‍💻 **Conhecimentos adquiridos neste laboratório:**

✅Criar uma Amazon VPC com duas sub-redes públicas

✅Criar um gateway de internet

✅Criar uma tabela de rota com uma rota pública para a internet

✅Criar um grupo de segurança

✅Iniciar uma instância do Amazon Elastic Compute Cloud (Amazon EC2)

✅Configurar uma instância do EC2 para hospedar um aplicativo web usando um script de dados do usuário

## 👩🏼‍💻 **Visão geral do Laboratório:**

✅Criar uma VPC, um gateway de internet, uma tabela de rota com uma rota pública para a internet e duas sub-redes públicas em duas Zonas de Disponibilidade (AZs) separadas.

## 👩🏼‍💻 **Execução do laboratório:**

✅Criei uma VPC, uma Sub-Redes públicas, uma tabela de rota e um gateway de internet;

✅Adicionei uma rota pública à tabela de rota;

✅Criei um grupo de segurança da VPC;

✅Criei uma instância do EC2 com um script de bootstrap para instalar e configurar os requisitos do aplicativo web;

✅Logo após acessei a tela do aplicativo via web. 

✅Finalizado o Laboratório.


## **Segue algumas capturas de tela desse Laboratório:**

![Laboratorio2](https://github.com/paolacsouza/curso-aws/blob/main/lab2/fluxo_de_trabalho_vpc.jfif)

![Laboratorio2](https://github.com/paolacsouza/curso-aws/blob/main/lab2/previsualizacao.jfif)

![Laboratorio2](https://github.com/paolacsouza/curso-aws/blob/main/lab2/tabelas_de_rota.jfif)

![Laboratorio2](https://github.com/paolacsouza/curso-aws/blob/main/lab2/grupo_de_seguranca.jfif)

![Laboratorio2](https://github.com/paolacsouza/curso-aws/blob/main/lab2/execucao_da_instancia.jfif)

![Laboratorio2](https://github.com/paolacsouza/curso-aws/blob/main/lab2/instancia.jfif)

![Laboratorio2](https://github.com/paolacsouza/curso-aws/blob/main/lab2/aplicativo_web.jfif)


## **_____________________________________________________________________________________________________**

## **Laboratório 3: Configurar um aplicativo web para usar um bucket do Amazon S3 e uma tabela do Amazon DynamoDB**

## 👩🏼‍💻 **Conhecimentos adquiridos neste laboratório:**

✅Criar um bucket do Amazon Simple Storage Service (Amazon S3)

✅Criar uma política de bucket do S3

✅Modificar um aplicativo para usar um bucket do S3

✅Fazer upload de um objeto para um bucket do S3

✅Criar uma tabela do Amazon DynamoDB

✅Testar um aplicativo usando uma interface da web do aplicativo

✅Gerenciar itens existentes do DynamoDB usando o Console de Gerenciamento da AWS

✅Crie itens em uma tabela do DynamoDB usando o Console de Gerenciamento da AWS


## 👩🏼‍💻 **Visão geral do Laboratório:**

✅Criar um bucket do Amazon S3, modificar a política dele,configurar um aplicativo de diretório para usar o bucket do S3, realizar teste na aplicação, criar uma tabela do Amazon DynamoDB, usar a interface da aplicação e o DynamoDB para criar itens na tabela e testar a funcionalidade da aplicação.

## 👩🏼‍💻 **Execução do laboratório:**

✅Criei um bucket do Amazon Simple Storage Service (Amazon S3)

✅E também criei uma política de bucket do S3

✅Modifiquei o aplicativo para usar um bucket do S3

✅Realizei o upload de umas imagens para meu bucket S3

✅Criei uma tabela do Amazon DynamoDB

✅Realizei teste no aplicativo usando a interface da web.

✅Gerenciei todos os itens existentes do DynamoDB usando o Console de Gerenciamento da AWS

✅Criei também os itens em uma tabela do DynamoDB usando o Console de Gerenciamento da AWS

✅Finalizado o Laboratório.


## **_____________________________________________________________________________________________________**

## **Laboratório 4: Configurar alta disponibilidade para seu aplicativo**

## 👩🏼‍💻 **Conhecimentos adquiridos neste laboratório:**

✅Analisar uma instância e um aplicativo web do Amazon Elastic Compute Cloud (Amazon EC2) e validar a configuração.

✅Crie um Application Load Balancer e um modelo de execução.

✅Configure um grupo do Amazon EC2 Auto Scaling.

✅Iniciar um modelo.

✅Realize um teste de estresse no aplicativo web para validar o dimensionamento.

## 👩🏼‍💻 **Visão geral do Laboratório:**

✅Criei um grupo de destino, um Application Load Balancer e um modelo de execução. Em seguida, configurei um grupo de Auto Scaling que usa o grupo de destino, o Application Load Balancer e o modelo de execução que criei. Por fim, testei o aplicativo com uma carga de trabalho simulada e 
fiquei observando o dimensionamento do aplicativo em tempo real.

## 👩🏼‍💻 **Execução do laboratório:**

✅Analisei uma instância do EC2 e um aplicativo web para validar a configuração

✅Criei um Application Load Balancer

✅Criei um modelo de execução

✅Criei um grupo de Auto Scaling

✅Testei o aplicativo



