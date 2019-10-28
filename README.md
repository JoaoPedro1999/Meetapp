# Meetapp - Desafio Bootcamp

Foi utilizado o git submodules, ou seja, são modulos separados que copõem o MeetApp, todos possuem um repositório especifico onde está incluso todo o código fonte.

## Frontend 
#### Instruções de Instalação

`` git clone `` 

Para baixar as dependências, utilize:

`` yarn `` 

Para rodar a aplicação, utilize:

`` yarn start ``

## Backend
#### Instruções de Instalação

`` git clone `` 

`` yarn `` 

#### Configurar um container para o Postgres e Redis

Após configurar o banco, utilize o comando abaixo para configurar as migrations:

`` yarn sequelize db:migrate ``

Para rodar a aplicação, utilize:

`` yarn dev ``

*A aplicação está rodando em uma instância na Google Cloud, o endereço da aplicação:* [http://104.154.247.88/](http://104.154.247.88/). *Toda configuração foi feita seguinda os módulos de deploy apresentados no Bootcamp. Por isso a configuração do API utilizada no axios segue esse endereço.* 


## Mobile
#### Instruções de Instalação

**O Aplicativo foi feito apenas para Android**

`` git clone `` 

`` yarn `` 

Para rodar a aplicação utilize 

`` react-native run-android ``



