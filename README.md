<h1 align="center">

Fast-API Hobby-Dev 🌆

</h1>

<p align="center">

<a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;

<a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;

<a href="#-rodando">Rodando</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;

<a href="#-como-contribuir">Como contribuir</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;

</p>

<a id="rocket-tecnologias"></a>

## 🚀 Tecnologias

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />

<img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" />

<img src="https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white" />

<img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" />

<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />

</div>

<br>

<a id="-projeto"></a>

## 💻 Projeto

Minha primeira API com o framework Fast-API, apenas possui intuito de aprendizado e testar a ferramenta.

<a id="-rodando"></a>

## Rodando o projeto 🌇

## Requerimentos:

- [Python](https://www.python.org/)

- [Docker](https://www.docker.com/)

## 📂 UM comando só:

Lembre-se de configurar o arquivo `.env` com os seus dados desejados.

Foi disponibilizado um arquivo `.env.example` para configurar o docker.

```
DATABASE_HOSTNAME=

DATABASE_PORT=

DATABASE_PASSWORD=

DATABASE_NAME=

DATABASE_USERNAME=



SECRET_KEY=

ALGORITHM=

ACCESS_TOKEN_EXPIRE_MINUTES=30
```

🐬 Comando:

```bash

docker-compose up --build -V

```

## ☕ Dicas:

Se você quiser acessar a documentação das aplicações, você pode acessar via algumas URLS.

Documentação da API:

http//localhost:8000/docs

<a id="-como-contribuir"></a>

## 🤔 Como contribuir

- Faça um fork desse repositório;

- Cria uma branch com a sua feature: `git checkout -b minha-feature`;

- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;

- Faça push para a sua branch: `git push origin minha-feature`.

Depois que o merge da sua pull request for feito, você pode deletar a sua branch.
