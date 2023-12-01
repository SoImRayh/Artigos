# Implementando CI-CD com gitHub actions e watchTower

![Actions logo](./media/Github-actions-logo.png)

# Objetivo
Implementar um pipeline que automatize o processo de criação de imagens docker de aplicações, push em um registry de
imagens docker, logo após essa imagem deve ser atualizada na máquina de produção de forma automática.

## Passos
 - [Aplicação base](#aplicação-base)
 - [Criando seu primeiro Workflow](#criando-seu-primeiro-workflow)
 - [Configurando para criar e publicar imagens docker](#configurando-para-criar-e-publicar-imagens-docker)
 - [Configurando a máquina de produção](#configurando-a-máquina-de-produção)
 - [Testando o pipeline](#testando-o-pipeline-de-cicd)

# Aplicação base

Para poupar tempo com coisas que não são o nosso foco desenvolvi uma API bem simples para não ocupar muito do nosso tempo.

## façam o fork do repositório [SoImRayh/temp](https://github.com/SoImRayh/temp)

Para iniciar com actiosn precisarei fazer commits direto no repositório.

## Sobre a aplicação

A aplicação é bem simples apenas um crud de um model Pessoa:

```java
public class Pessoa {
    
    private String nome;
    private String sobrenome;
    
}
```

E uma pagina html simples retornada quando dada um get no caminho "/";

```java
 @GetMapping("")
public ModelAndView home(){
 return new ModelAndView("index.html")
}
```

# Criando seu primeiro Workflow

Workflow é nada mais que um pipeline de serviços com diversos estágios, mas para iniciar vá até o repositório no github e na aba actions

# Configurando para criar e publicar imagens docker
# Configurando a máquina de produção
# Testando o pipeline de CICD

#Referências
 - [GitHub actions]()
 - [Watchtower]()
