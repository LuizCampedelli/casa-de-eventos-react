# Sistema de casa de eventos | React Vite Node Docker

![Print da Homepage](https://i.ibb.co/0BLwdMW/Screenshot-2024-02-19-at-16-30-28.png)

## Tecnologias Utilizadas

- React
- Vite
- Node v20.5.1

## Dependências Utilizadas

- React Router
- Styled Components
- Axios
- React Toastify
- Json Server

## Instruções de Instalação

Clonar o projeto com o comando abaixo:

```sh
git clone git@github.com:LuizCampedelli/casa-de-eventos-react.git
```

Entrar na pasta do projeto

```sh
cd casa-de-eventos-react
```

Instalar as dependencias

```sh
npm install
```

## Instruções para rodar o projeto

Digitar o comando para criar a imagem do docker baseado nos requisitos do Dockerfile

```sh
docker buildx buld -t casa-de-eventos-react .
```
Digitar o comando para rodar a imagem do docker em uma porta especifica


```sh
docker run -d -p 5173:5173 casa-de-eventos-react
```

### _Pronto! Seu projeto já estará rodando no endereço

```sh
http://localhost:5172
```
