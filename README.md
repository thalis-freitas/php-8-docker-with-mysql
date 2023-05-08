# PHP 8 no docker com MySQL

Este repositório tem como objetivo fornecer um guia passo a passo para auxiliar na utilização do PHP 8 em conjunto com o Docker, MySQL e PHPMyAdmin. Com as instruções fornecidas neste repositório, é possível criar um ambiente de desenvolvimento PHP com Docker e MySQL de forma rápida e fácil.

OBS: **Caso ainda não tenha instalado o Docker, você pode baixá-lo e instalá-lo a partir do [site oficial do Docker](https://www.docker.com/).**

## Passo a passo

1 - Clone o projeto:

```
git clone git@github.com:Thalis-Freitas/php-8-docker-with-mysql.git
```

2 - Renomeie o nome do projeto como preferir:

```
mv php-8-docker-with-mysql nome_do_projeto
```

3 - Entre no diretório do projeto:

```
cd nome_do_projeto
```

4 - Certifique-se de que o Docker esteja em execução em sua máquina e suba os containers:

```
docker compose up
```

5 - Acesse http://localhost:8000/

A página deve exibir o texto: `Hello PHP!`
