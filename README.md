<p align="center">
   <img width="300px" src="./.github/logo.svg" alt="Trip" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Typescript-v3.7.2-blue" />  
  <img src="https://img.shields.io/badge/React-v16.13.1-lightblue" />
  <img src="https://img.shields.io/badge/Leaflet-v1.7.1-lightgreen" />
  <img src="https://img.shields.io/badge/Axios-v0.20.0-lightgrey" />
  <img src="https://img.shields.io/badge/Commitizen-v4.2.1-lightgrey" />
  <img src="https://img.shields.io/badge/Yarn-v1.22.5-lightblue" />
</p>

## Tabela de Conteúdo

- [Tabela de Conteúdo](#tabela-de-conte%C3%BAdo)
- [Sobre o Projeto](#sobre-o-projeto)
  - [Feito Com](#feito-com)
- [Começando](#come%C3%A7ando)
  - [Pré-requisitos](#pr%C3%A9-requisitos)
  - [Estrutura de Arquivos](#estrutura-de-arquivos)
  - [Instalação](#instala%C3%A7%C3%A3o)
  - [Frontend](#frontend)
  - [API](#api)
- [Contribuição](#contribui%C3%A7%C3%A3o)
- [Contato](#contato)

## Sobre o Projeto

Aplicação é uma plataforma para encontrar orfanatos e casas de acolhimento institucional na sua cidade, visando facilitar o processo de ajuda e visitação à estes lugares. As instituições cadastram seus dados e informações sobre o processo de visitas, as pessoas acessam estes dados através da plataforma e se dirigem aos orfanatos.

<img src="./.github/landing.png" width="600px" />

### Feito Com

Abaixo segue o que foi utilizado na criação deste projeto:

- [Typescript](https://www.typescriptlang.org/) - TypeScript é um superconjunto de JavaScript desenvolvido pela Microsoft que adiciona tipagem e alguns outros recursos a linguagem. Anders Hejlsberg, arquiteto da linguagem C# e criador das linguagens Delphi e Turbo Pascal, trabalhou no desenvolvimento do TypeScript.

- [React](https://pt-br.reactjs.org/) - O React é uma biblioteca JavaScript de código aberto com foco em criar interfaces de usuário em páginas web. É mantido pelo Facebook, Instagram, outras empresas e uma comunidade de desenvolvedores individuais. É utilizado nos sites da Netflix, Imgur, Feedly, Airbnb, SeatGeek, HelloSign, Walmart e outros.

- [Leaflet](https://leafletjs.com/) - Leaflet é a biblioteca JavaScript de código aberto líder para mapas interativos compatíveis com dispositivos móveis. Pesando apenas cerca de 39 KB de JS , ele tem todos os recursos de mapeamento que a maioria dos desenvolvedores precisa.

- [Axios](https://www.npmjs.com/package/axios) - Axios é um cliente HTTP baseado em Promises para fazer requisições. Pode ser utilizado tanto no navegador quando no Node.js. É um projeto open source e está sendo bem mantido pela comunidade.

- [Commitizen](https://yarnpkg.com/) - O commitizen é um pacote que facilita a criação de mensagens de commit.

- [Yarn](https://yarnpkg.com/) - Yarn é um gerenciador de pacotes que também atua como gerente de projeto. Quer você trabalhe em projetos únicos ou grandes monorepos, como um aquarista ou um usuário corporativo, temos o que você precisa.

## Começando

Para conseguir utilizar ou visualizar o projeto, seja através do Visual Studio Code ou outro editor de código, siga os passos abaixo:

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
- É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado no computador
- É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado no computador
- É **preciso** ter um gerenciador de pacotes seja o **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.

### Estrutura de Arquivos

A estrutura de arquivos está da seguinte maneira:

```bash
happy-web
├── public/
│        └── index.html
├── src/
│     ├── assets/
│     │         ├── images/...
│     │         └── styles/
│     │               └── global.css
│     ├── components/
│     │            └──  Sidebar/
│     │                       ├── index.tsx
│     │                       └── styles.css
│     ├── pages/
│     │      ├── CreateOrphanage/
│     │      │         ├── index.tsx
│     │      │         └── styles.css
│     │      ├── Landing/
│     │      │         ├── index.tsx
│     │      │         └── styles.css
│     │      ├── Orphanage/
│     │      │           ├── index.tsx
│     │      │           └── styles.css
│     │      └──  OrphanageMap/
│     │                      ├── index.tsx
│     │                      └── styles.css
│     ├── services/
│     │         └── api.ts
│     │ 
│     ├── utils/
│     │      └── mapIcon.ts
│     │  
│     ├── App.tsx
│     ├── index.tsx
│     ├── react-app-env-ts
│     └── routes.tsx
├── .gitignore
├── README.md
├── package.json
├── tsconfig.json
└──yarn.lock
```

### Instalação

Para instalar esse projeto, o processo é bem simples. Basta utilizar o seguinte comando no terminal:

```bash
# Clone este repositório
$ git clone https://github.com/MTevangelista/happy-web.git
```

### Frontend


```bash
# Instale as depedencias
$ yarn ou npm install

# Rode a aplicação
$ yarn serve ou npm run serve

# A aplicação web inciará na porta: 3000 - acesse http://localhost:3000
```

### API

O back-end do projeto foi desenvolvido com: Typescript, Node.Js, Express, TypeOrm e SQLite3.

- Repositório do projeto: https://github.com/MTevangelista/happy-api

---

## Contribuição

Contribuições são o que fazem a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/FeatureIncrivel`)
3. Adicione suas mudanças (`git add .`)
4. Comite suas mudanças (`git commit -m 'Adicionando uma Feature incrível!`)
5. Faça o Push da Branch (`git push origin feature/FeatureIncrivel`)
6. Abra um Pull Request

## Contato

👤  **Matheus Evangelista**

[![Github Badge](https://img.shields.io/badge/-Github-000?style=round-square&logo=Github&logoColor=white&link=https://github.com/MTevangelista)](https://github.com/MTevangelista)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=round-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/matheus01/)](https://www.linkedin.com/in/matheus01/)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-c14438?style=round-square&logo=Gmail&logoColor=white&link=mailto:matheusevangelistadev@gmail.com)](mailto:matheusevangelistadev@gmail.com)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-ba164a?style=round-square&logo=Instagram&logoColor=white&link=https://www.instagram.com/_matheusrj/?hl=pt-br)](https://www.instagram.com/_matheusrj/?hl=pt-br)
