# Projeto Meu GithubSearch

Projeto desenvolvido na Semana 14 do Curso de FrontEnd <img src="src/assets/reprograma-fundos-claros.png" alt="logo reprograma" width="200">, utilizando React.js, cujo objetivo era criar um site pessoal com meus repositorios do Github.

Neste projeto foram utilizados os seguintes conteúdos:

  - [1. Eventos]()
  - [2. Listas e Keys]()
  - [3. Introdução aos Hooks]()
    - [3.1. useState]()
    - [3.2. useEffect]()

# Índice

- [Apresentação](#Apresentação)
- [DESCRIÇÃO DO PROJETO](#Descrição-Do-Projeto)
- [TECNOLOGIAS UTILIZADAS](#Tecnologias-Utilizadas)
- [PASSO A PASSO UTILIZADO](#Passo-A-Passo-Utilizado)
- [FUNCIONALIDADES IMPLEMENTADAS](#Funcionalidades-Implementadas)
- [IMPLEMENTAÇÕES FUTURAS](#Implementações-Futuras)
- [COMO RODAR O PROJETO](#Como-Rodar-O-Projeto)
- [CONFIRA O RESULTADO ](#Confira-O-Resultado)

# Apresentação

### Quem é Flaviana?

![image](https://github.com/FlavianaFXT/ProjetoFinal-reprograma/assets/113718720/1e13d5e7-b1b4-4701-a689-ec293ec77ea1)

Flaviana Ferraz é uma sertaneja de Pernambuco morando no sertão da Paraiba, formada em Gestão Ambiental e Mestre em Recursos Hídricos, após mais de 10 anos de formada, aos 34 anos, decidiu fazer transição de carreira. Hoje, empreendedora e aluna {reprograma} trilhando os caminhos do Desenvolvimento FrontEnd.

#### Contatos

- [E-mail](flaviferraz@yahoo.com.br)
- [LinkedIn](https://www.linkedin.com/in/flaviana-ferraz-frontend)
- [GitHub](https://github.com/flavianafxt)


# DESCRIÇÃO DO PROJETO

## 🧠 Contexto

O objetivo desse site era utilizar os conceitos aprendidos em sala durante a semana 14 do curso de FrontEnd da Reprograma para desenvolver uma página pessoal com acesso aos reposi´torios do github (consumo de API) e mecanismo de busca deles.

![image](https://github.com/FlavianaFXT/GithubSearch2/assets/113718720/56da2255-00c7-4377-a43d-edc9ba244c11)

![image](https://github.com/FlavianaFXT/GithubSearch2/assets/113718720/bae9f1af-b3d7-4893-b921-afa6ac30a30a)

## 🧠 Estrutura do projeto

![image](https://github.com/FlavianaFXT/GithubSearch2/assets/113718720/3a4e0b86-8251-4661-8543-fa01fc2fb240)
![image](https://github.com/FlavianaFXT/GithubSearch2/assets/113718720/f5a3e4d4-0151-4d3c-8041-ec7dbe87f679)

# TECNOLOGIAS UTILIZADAS

| Ferramenta | Descrição |
| --- | --- |
| `ReactJS` | framework web|
| `Vite` | gerador de projeto de front-end|
| `npm` | gerenciador de pacotes|
| `Axios` | consumo de API do Github|
| `Git` | Gerenciador de vercionamento|
| `Github` | Hospedagem do código fonte integrado com gerenciador de versionamento|
| `Vercel` | deploy do projeto|

# PASSO A PASSO UTILIZADO

1️⃣ Criação de repositorio no github e clone na maquina em que trabalhei no projeto através do Git Bash
2️⃣ Start do projeto na maquina utilizando o VS Code e seu terminal, atraves dos comandos de iniciação vite e node
 
  ```bash
  npm create vite@latest nome-projeto -- --template react
  ```
   ```bash
  cd nome-projeto
   ```
  ```bash
    npm i
  ```
  ```bash
     npm run dev
  ```
  
3️⃣ Exclusão de arquivos do projeto que não faremos uso e inserção de algum elemento em App.jsx para ver se o projeto está funcionando
4️⃣ Renderização dos componentes que formam a página
5️⃣ Consumo de API do Github para renderização dos repositórios na página
6️⃣ Implantação do mecanismo de busca de repositórios através de termos inseridos no campo de busca e renderização destes na página
7️⃣ Adicionar todas as modificações a cada etapa e subir no GitHub
 ```bash
 git add .
 ```
 ```bash
 git commit -m "comentario"
```
 ```bash
 git push
```

8️⃣ Deploy do projeto no Vercel

# FUNCIONALIDADES IMPLEMENTADAS

✔️ Renderização de perfil pessoal personalizado
✔️ Renderização dos meus repositórios do github através do consumo de API
✔️ Mecanismo de busca de repositórios através de termos digitados no campo de busca e renderização dos repositórios que contêm os termos pesquisados

#  IMPLEMENTAÇÕES FUTURAS

✖️ Mecanismo de busca de qualquer perfil no github e renderização na página
✖️ Renderização dos repositórios do perfil pesquisado 


# COMO RODAR O PROJETO

Para rodar esse projeto em sua máquina, siga os passos a seguir:

1️⃣ Realize o fork desse repositorio

2️⃣ Clone na sua máquina

3️⃣ Entre no diretório do repositorio clonado e as dependências do projeto, com o comando:
```bash
                                           npm install ou npm i
```

4️⃣ Por fim rode o projeto:
```bash
                           npm run dev
```

O navegador será aberto automaticamente usando a porta localhost:3000 
  
# CONFIRA O RESULTADO 

https://meu-github-search-mfml8f6tw-flavianafxt.vercel.app/
