# CheckPoint 2
Aplicação Java com container e Banco de dados


## Pré-requisitos

- Java 17 +
- Docker 
- Acesso a internet
- Acesso ao docker Hub

## Instalação

#### Clone

```
git clone https://github.com/
git clone https://github.com/
git clone https://github.com/
```


## Execução


#### Docker

Criação de imagem

```
docker build -t checkpoint2 .
```

###executar container 

```
Executar em DEV
docker run -d -p 8080:8080 -e PROFILE=dev 

Executar em STG
docker run -d -p 8080:8080 -e PROFILE=stg 

Executar em PRD
docker run -d -p 8080:8080 -e PROFILE=prd 
```



#### Navegação

* Base

	http://localhost:8080

* Endpoint que retorna a tela do banco de dados H2

	http://localhost:8080/h2-console


## Alunos

- João Pedro Marson RM93432
- Gabriel Cavalcanti Pereira RM94494
- Caio Willeman - RM93407


## Fontes

https://stackoverflow.com
