# Evandro Rodrigues de Melo Braga

## Introdução
Venho da área de hotelaria, porém em 2019 me interessei pela área de tecnologia, então em julho de 2019 comecei a cursar Analise e Desenvolvimento de Sistemas pela Fatec de São José dos Campos, já no segundo mês de faculdade entrei em um estágio não remunerado onde tive a oportunidade de conhecer os processos de uma empresa de desenvolvimento que trabalhava com a metodologia ágil, permaneci lá por 6 meses, desde então eu não parei mais de trabalhar, atualmente atuo como desenvolvedor back-end trabalhando com node, criando e mantendo sistemas monolíticos e micro serviços

## Meus Projetos

### Em 2019-2

![fatec](https://user-images.githubusercontent.com/56441371/138716775-60b0f192-2c2b-476a-bda1-ffbd2d230756.jpeg)

A primeira parceira nos projetos foi a Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal que propôs um desafio com objetivo de identificar uma dor e resolver integrando um hardware com um aplicativo móvel

O **Smart Irrigation** (do inglês, Irrigação Inteligente) é um sistema que permite efetuar uma irrigação de maneira inteligente, ou seja, sem a necessidade da interferência de terceiros, buscando economia ao agricultor uma vez que a irrigação é feita com a quantidade exata de água e com a automatização também economiza mão de obra humana. Dentre suas funcionalidades estão a definição em tempo real das variáveis ambientais (Temperatura, Umidade e Luminosidade), podendo também definir e salvar um perfil de irrigação compatível de acordo com a necessidade do agricultor. 

![image](https://user-images.githubusercontent.com/56441371/133184672-ed21bebc-f8b7-4bcc-8555-7a4131c0c210.png)

## Tecnologias Utilizadas

### Hardware

A escolha do microcontrolador Arduino Uno foi escolhido pois possui uma quantidade enorme de sensores e componentes que você pode utilizar nos seus projetos. Grande parte do material utilizado está disponível em módulos, que são pequenas placas que contém os sensores e outros componentes auxiliares como resistores, capacitores e leds. Existem também os chamados Shields, que são placas que você encaixa no Arduino para expandir suas funcionalidades. 
Tendo em vista estas facilidades e funcionalidades do Arduino, foram então escolhidos os sensores compatíveis com este modelo para montagem do projeto.

A linguagem de programação base do arduino é o C++ que foi utilizado para programar o hardware 

### Software
Kodular: Um site capaz de trabalhar com programação em blocos para gerar aplicativos para plataforma móvel Android, foi usado para o desenvolvimento do aplicativo mobile

Firebase: Um serviço de nuvem NoSQL foi utilizado para armazenar as respostas de um sistema de avaliação que tinha no aplicativo

![image](https://user-images.githubusercontent.com/56441371/133184941-33e72fab-ff72-445f-9e33-36bca57a429b.png)

## Contribuições Pessoais
Nesse projeto eu fiquei responsável por desenvolver a interface gráfica e suas funcionalidades, de início eu pensei como seria a usabilidade do usuário, então para o agricultor configurar a quantidade ideal de luminosidade, temperatura e calor da terra usei sliders para que fosse simples e fácil definir os parâmetros de acordo com a necessidadedo agricultor

Inicialmente criei um wireframe e em seguida a parte visual usando o kodular, depois precisei integrar com o hardware para isso fiz muitas pesquisas a fim de entender como essa integração funcionava, descobri que a melhor forma seria através de bluetooth, tive ajuda dos outros integrantes do grupo na integração, feito isso precisei criar as lógicas usando programação em blocos inicialmente criando as variáveis contendo os parâmetros dos sliders e depois salvando esses valores no banco de dados firebase para que possam ser usados e enviados para o arduino

O app contava também com um sistema de avaliação para que os usuários pudessem enviar uma nota de 0 a 10 e essa avaliação também era salva no banco de dados, foi o meu primeiro contato com programação em blocos e com essa experiência aprendi muito sobre lógica de programação básica e como as coisas funcionavam em uma aplicação, como o kodular usa programação em blocos não tenho o código no git, porém segue o print do código.


## Hard Skills
- Programação em blocos: Aprendi a utilizar com ajuda;

- Wireframes: Aprendi a fazer com autonomia;

- Firebase Database: Aprendi a utilizar com ajuda;

- Documentação técnica: Primeiro contato aprendi a fazer com ajuda;

- Metodologias Scrum: Conceitos aprendidos na prática.

## Soft Skills
- Organização do projeto: Esse foi o meu primeiro contato desenvolvendo um projeto do zero então a organização foi fundamental utilizando um kanban para definir as tarefas e o tempo;

- Resiliência: Como eu não tinha conhecimento prévio em programação foi muito difícil desenvolver algo do zero, por muitos momentos achei que não iria conseguir, porém com bastante esforço e persistência saiu um grande trabalho de primeiro semestre;

- Trabalho em equipe: Para um melhor resultado o projeto contou com 4 participantes, cada com uma função, fazendo o que foi combinado desde o início;

- Comunicação: Como eramos em 4 foi imprescindível uma boa comunicação com reuniões durante as aulas para alinhar como estava andamento de cada um no projeto, sempre sendo solicito ajudando e recebendo ajuda.


### Em 2020-1

![spc](https://user-images.githubusercontent.com/56441371/138716818-714a4427-f22d-4602-8eae-3a2d6ec8e70c.png)

No segundo semestre a empresa parceira foi o SPC que nos enviou uma base de dados propondo um desafio de gerar valor com esses dados

Assim nasceu o **DP Standardize** uma ferramenta para o Data Preparation que é a preparação e padronização de grandes lotes de dados antes de ser usados em projetos futuros, então o projeto foi pensado e desenvolvido visando a governança de dados, sendo capaz de analisar qualquer tabela xlsx e csv

![marketing_PI_11111](https://user-images.githubusercontent.com/57918707/87260544-dbc5ef80-c488-11ea-8987-faec80939a8b.png)

https://github.com/EvandroRBR/Tratamento-de-dados-SPC


## Tecnologias Utilizadas

![tecnologias_PI](https://user-images.githubusercontent.com/56441214/87261156-8c34f300-c48b-11ea-89cf-a96eef22661c.png)

- Electron - Framework para criação aplicações desktop que possibilita trabalhar com tecnologias da Web como Javascript, HTML e CSS, facilitndo o desenvolvimento da interface gráfica;

- Python - Linguagem Open-Source de propósito geral usado bastante em data science, machine learning, desenvolvimento de web, desenvolvimento de aplicativos, automação de scripts, como é uma linguagem excelente para anĺise de dados resolvemos utiliza-la para o data preparation;

- NodeJs - O NodeJs pode ser definido como um ambiente de execução Javascript server-side, Utilizamos o essa ferramenta pois o Electron é um Framework que necessita dela para funcionar.

## Contribuições Pessoais

Nesse projeto atuei como Product Owner entendendo a necessidade do cliente, coletando informações de como desenvolver o projeto visando a satisfação do usuário final, fazendo o levantamento dos requisitos e ajudando a equipe em tudo o que foi necessário sobre o entendimento do projeto, também ajudei a estruturar e definir as responsabilidades junto com o Scrum Master

Na parte de desenvolvimento ajudei a desenvolver o código responsável em análisar e preparar os dados utilizando Python e também a integras com o Electron o que foi um grande desafio pois não encontramos muito conteúdo voltado a essa integração entre Python e Electron

## Hard Skills

- Tratamento de dados com Python: Aprendi a fazer com autonomia;

- Construção do Aplicativo Desktop: Aprendi a fazer com autonomia;

- Integração com Electron: Aprendi a fazer com ajuda;

- Documentação do projeto: Aprendi a fazer com autonomia;

- Wareframes: Aprendi a fazer com autonomia;

- Metodologia Ágil SCRUM: Aprendi a fazer com autonomia.

## Soft Skills

- Organização do projeto: Com uma equipe de 5 pessoas e com um problema de escopo aberto foi necessário definir muito bem qual seria a atuação de cada participante para que todos os requisitos fossem desenvolvidos e o trabalho finalizado com sucesso;

- Resiliência: Foi meu primeiro contato como desenvolvedor com uma empresa real e com um desafio grande foi necessário muita determinação pois não sabíamos como desenvolver o que era necessário, isso devido a falta de experiência pois eramos alunos do segundo semestre ;

- Trabalho em equipe: Como o desafio que era bem novo para todos nós, foi crucial a participação de todos ajudando em tudo o que era necessário;

- Comunicação: Como eramos em 5 foi imprescindível uma boa comunicação com reuniões quase todos os dias, já que estávamos no sistema de ensino remoto por conta da pandemia de COVID 19, para alinhar como estava andamento de cada um no projeto, sempre sendo solicito ajudando e recebendo ajuda.

### Em 2020-2
![visiona](https://user-images.githubusercontent.com/56441371/138779058-6661a3d5-a8a1-4e51-8c3d-8962d2055ee8.jpeg)

No Terceiro semestre a empresa parceira foi a Visiona que nos enviou um desafio que foi em desenvolver sistema web ETL (Extract, Transform and Load)

A **VisGEO** é uma ferramenta web onde usuário pode armazenar dados geográficos contidos em shapefiles, para isso a ferramenta transforma esses dados em um formato compatível com o que o banco, sendo possível também recuperar o que está salvo e convertendo novamente para um shapefile

![ViaGeo - Capa](https://user-images.githubusercontent.com/56441371/93688444-5704dc80-fa9c-11ea-8bed-fdac35ce7337.png)

https://github.com/EvandroRBR/VisGeo-ETL

## Tecnologias Utilizadas

![VisGeo - Techs](https://user-images.githubusercontent.com/56441371/93688825-3c803280-fa9f-11ea-9408-bd07d27aad71.png)

- NodeJs - O NodeJs pode ser definido como um ambiente de execução Javascript server-side, Utilizamos o Node para fazer o CRUD de usuários;

- Python - Linguagem Open-Source de propósito geral usado bastante em data science, machine learning, desenvolvimento de web, desenvolvimento de aplicativos, automação de scripts utilizamos essa linguagem pois existem muitas bibliotecas que ajudariam no desenvolvimento do projeto como GeoPandas, PyShp entre outras;

- Flask - Flask é um micro framework que utiliza a linguagem Python para criar aplicativos Web, utilizamos essa ferramenta pois já tínhamos alguma vivência com esse framework e no inicio do projetos os professores sugeriram usar python que é a Linguagem do Flask;

- PostGis - Uma extensão espacial Open-Source. Sua construção é feita sobre o sistema de gerenciamento de banco de dados objeto relacional (SGBDOR) PostgreSQL, que permite o uso de objetos GIS (Sistemas de Informação Geográfica), utilizamos essa ferramenta por ser perfeita para o propósito de armazenar dados geo referenciados;

- ReactJs - Uma biblioteca JavaScript declarativa, eficiente e flexível para a criação de interfaces de usuário utilizamos ReactJs pois é uma grande ferramenta de desenvolvimento Front-end, muito utilizada no mercado e também era a ferramenta que o grupo tinha maior conhecimento;

- StyledComponents - Uma biblioteca que utiliza o conceito de CSS-in-JS, ou seja, que nos permite escrever códigos CSS dentro do Javascript sendo a base de toda a estilização do projeto;

- Docker - É uma forma de virtualizar aplicações no conceito de “containers”, trazendo da web ou de seu repositório interno uma imagem completa, utilizamos docker para facilitar a instalação do sistema entre os desenvolvedores.


## Contribuições Pessoais

Assim como no semestre anterior, nesse projeto atuei como Product Owner entendendo a necessidade do cliente, coletando informações de como desenvolver o projeto visando a satisfação do usuário final, fazendo o levantamento dos requisitos e ajudando a equipe em tudo o que foi necessário sobre o entendimento do projeto, também ajudei a estruturar e definir as responsabilidades junto com o Scrum Master

Na parte de desenvolvimento ajudei a buscar melhores maneiras de armazenar os dados dos shapefiles, porém minha maior contribuição foi na criação do CRUD de usuários desenvolvendo também a parte de autenticação contando com um token gerado em cada nova sessão garantindo assim maior segurança aos usuários

## Hard Skills

- CRUD: Aprendi a fazer com autonomia;

- Docker: Aprendi a usar com autonomia;

- Flask: Aprendi a usar com ajuda;

- Python: Aprendi a usar com ajuda;

- Documentação do projeto: Aprendi a fazer com autonomia;

- Wareframes: Aprendi a fazer com autonomia;

- Metodologia Ágil SCRUM: Aprendi a fazer com autonomia.

## Soft Skills

- Organização do projeto: Com uma equipe de 9 pessoas e um desafio com mais requisitos técnicos a organização foi um pouco mais desafiadora, porém com a experiência adquirida nos semestres anteriores conseguimos definir bem qual seria a atuação de cada participante para que todos os requisitos fossem desenvolvidos e o trabalho finalizado com sucesso;

- Resiliência: Assim como os outros projetos a VisGEO foi bem desafiadora e sempre com a ajuda de todos seguimos firmes no propósito de desenvolver esse sistema e aprender cada vez mais;

- Trabalho em equipe: Foi um desafio muito novo para todos nós, pois não sabíamos o que era um shapefile e no início não tínhamos ideia de como resolver esse problema, então com o apoio e determinação de todos entregamos tudo o que foi proposto no início do semestre.

- Comunicação: Como eramos em 5 foi imprescindível uma boa comunicação com reuniões quase todos os dias, já que estávamos no sistema de ensino remoto por conta da pandemia de COVID 19, para alinhar como estava andamento de cada um no projeto, sempre sendo solicito ajudando e recebendo ajuda.



