![](https://developrogramming.com/wp-content/uploads/2021/11/spring-framework.jpg)

# Desenvolvendo sua primeira aplicação web java usando ecossistema spring.

## O que vamos aprender?
Nesse artigo nosso objetivo é desenvolver nossa primeira aplicação java usando usando o ecossistema Spring, aprenderemos os conceitos básicos de como desenvolver com a ferramenta maven.

## Spring ou spring boot?
Quando estamos falando de desenvolvimeto web usando java com toda certeza estamos falando de Spring, contudo há coisas que devem ser esclarecidas, rotineiramente se é colocado spring e spring boot como tecnologis concorrentes "concorrentes", o que é falso, e explicarei brevemente a responsabilidade de cada.

### O ecossitema spring
Em todas as linguagens de programação com implementações web se tem frameworks que fonecem suporte a vários estilos de programações, e em java não é diferente, o que muda é que podemos dizer que todos (ao menos os mais utilizados) frameworks destinados a implementações web em java são feitos usando como base o framework spring, especificamente spring core e usando as api's que ele nos fornece são feitas as implementações dos demais framework que serão apresentados no futuro.

![](https://media.geeksforgeeks.org/wp-content/uploads/Spring-Framework-Architecture.png)

O spring boot vem para amenizar uma dor de tempos que era fazer o start usando spring, anteriormente perdia-se horas de trabalho fazendo as configurações iniciais para ter um "Hello world" na tela, e com spring boot se é adotado configurações feitas por convenção, ou seja são configurações que suprem a maioria das aplicações que vao ser desenvolvidas e se falso ele fornece uma grande ajuda para configura-las

O que podemos cravar é que o spring boot é na verdade um ponto de partida padrão para desenvolver usando spring evitando assim a perda de horas de trabalho configurando em que porta o serviço será exposto etc.

Finalizando, spring e spring boot não são concorrentes, mas sim algo bem fundamentar no desenvolvimento atual usando essa tecnologia, com isso devidamente explicado vamos fazer o nosso "Hello world".

## Mão na massa!

para iniciarmos nosso projeto iremos utilizar de mais uma ferramenta bastante popular dentre os programadores spring,  o [Spring Initializr](https://github.com/spring-io/initializr/) ele nos fornece um start muito mais rápido, (lembra muito os npx create project no npm-JS por exemplo),
para iniciar navegue ao site [Official Spring Initializr](https://start.spring.io/) e selecione as seguintes opções:
 - Project : Maven
 - Language : Java
 - Spring Boot: 3.1.2
 - project metadata:
    - Group: br.edu.ifg
    - Artifact: hello-world

## Sobre as escolhas:
### Maven
É o principal gerenciador de dependecias ou gerenciador de pacotes do java no usamos essa ferramenta para dar o build da nossas aplicaçoes java, e em fase de desenvolvimento também é ele quem oferecerá um build de desenvolvimento.
### Spring boot
A versão que iremos utilizar do Spring boot, vai ser ele que nos fará nos preocupar somente com desenvolver código no primeiro momento.
### Metadata: 
Esses dados são de respeito do nome do nosso projeto, basicamente definimos o grupo como sendo o lugar a que se destina a aplicação e o Artifact o nome no artefato pertencente ao group.

## Depedências
No lado direito da tela encontrará um botão para adicionar depedências que são como bibliotecas de códigos ou um pacote de código já feitos anteriormente e que na maioria dos casos funcionam hehe.

Para iniciarmos vamos utilizar do Spring do [Spring Web](https://docs.spring.io/spring-boot/docs/current/reference/html/web.html) e [Lombok](https://projectlombok.org/) selecione essas duas depedências e clique em 'GENERATE', que será iniciado o download de um arquivo .rar basta somente extraí-lo em uma pasta de sua preferência e abrir a pasta com seu editor de código favorito.

![Imagem]()

