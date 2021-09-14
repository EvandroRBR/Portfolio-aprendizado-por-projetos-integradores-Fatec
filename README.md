# Projeto Integrador: 2019-2
**Smart Irrigation**

## Parceiro Acadêmico
Fatec Prof. Jessen Vidal 

## Visão do Projeto (Equipe)

O objetivo do projeto consiste em integrar um hardware com um aplicativo móvel.</br>
Este projeto é a implementação do sistema Smart Irrigation (do inglês, Irrigação Inteligente) integrado a um aplicativo mobile. Este sistema permite efetuar uma irrigação de maneira inteligente, ou seja, sem a necessidade da interferência de terceiros. Dentre suas funcionalidades estão a definição em tempo real das variáveis ambientais (Temperatura, Umidade e Luminosidade), ou salvar um perfil de irrigação compatível de acordo com a necessidade do usuário. 


## Tecnologias adotadas na solução (Equipe)

### Hardware
A escolha do microcontrolador Arduino Uno foi escolhido pois possui uma quantidade enorme de sensores e componentes que você pode utilizar nos seus projetos. Grande parte do material utilizado está disponível em módulos, que são pequenas placas que contém os sensores e outros componentes auxiliares como resistores, capacitores e leds. Existem também os chamados Shields, que são placas que você encaixa no Arduino para expandir suas funcionalidades. 
Tendo em vista estas facilidades e funcionalidades do Arduino, foram então escolhidos os sensores compatíveis com este modelo para montagem do projeto.

![image](https://user-images.githubusercontent.com/56441371/133184672-ed21bebc-f8b7-4bcc-8555-7a4131c0c210.png)

### Software
Para o desenvolvimento do aplicativo mobile, foi utilizado o Kodular, que é um site capaz de trabalhar com programação em blocos para gerar aplicativos para plataforma móvel Android, também usamos o firebase para armazenar as resposta de um sistema de avaliação que tinha no aplicativo.

![image](https://user-images.githubusercontent.com/56441371/133184941-33e72fab-ff72-445f-9e33-36bca57a429b.png)



## Contribuições pessoais (Individual)
Nesse projeto eu fiquei responsável por desenvolver a interface gráfica e suas funcionalidades, de início eu pensei como seria a usabilidade do usuário, então para ele configurar a quantidade de luminosidade, temperatura e calor da terra usei sliders para que fosse simples e fácil definir os parâmetros de acordo com a necessidade, então inicialmente criei um wareframe e em seguida a parte visual usando o kodular, depois precisei integrar com o hardware para isso fiz muitas pesquisas a fim de entender como essa integração funcionava, descobri que a melhor forma seria através de bluetooth, tive ajuda dos outros integrantes do grupo na integração, feito isso precisei criar as lógicas usando programação em blocos inicialmente criando as variáveis contendo os parâmetros dos sliders e depois salvando esses valores no banco de dados firebase para que possam ser usados e enviados para o arduino, o app contava também com um sistema de avaliação para que os usuários pudessem enviar uma nota de 0 a 10 e essa avaliação também era salva no banco de dados, foi o meu primeiro contato com programação em blocos e com essa experiência aprendi muito sobre lógica de programação básica e como as coisas funcionavam em uma aplicação, como o kodular usa programação em blocos não tenho o código no git, porém segue o print do código.

![app](https://user-images.githubusercontent.com/56441371/132858474-30420bff-2b85-49d8-b23a-27c2f65bc89c.jpg)


## Aprendizados Efetivos (Individual)
- Programação em blocos: Aprendi a utilizar com ajuda;
- Wireframes: Aprendi a fazer com autonomia;
- Firebase Database: Aprendi a utilizar com ajuda;
- Documentação técnica: Primeiro contato aprendi a fazer com ajuda;
- Metodologias Scrum: Conceitos aprendidos na prática.

