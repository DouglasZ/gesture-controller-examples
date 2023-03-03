# JSExpertMax Gesture Controller

## Preview

<img width=100% src="./initial-template/assets/demo-template-lg.gif">

## Live demo

- [Projeto 01](https://douglasz.github.io/gesture-controller-examples/classes/classes01)
- [Projeto 02](https://douglasz.github.io/gesture-controller-examples/classes/classes02)
- [Projeto 03](https://douglasz.github.io/gesture-controller-examples/classes/classes03)
- [Projeto 04](https://douglasz.github.io/gesture-controller-examples/classes/classes04)

## Pre-reqs

- Este projeto foi criado usando Node.js v19.6

## Running

- Execute `npm ci` na pasta que contém o arquivo `package.json` para restaurar os pacotes
- Execute `npm start` e em seguida vá para o seu navegador em [http://localhost:3000](http://localhost:3000) para visualizar a página acima

## Checklist Features

- Titles List

  - [x] - Campo para pesquisa não deve travar ao digitar termo de pesquisa
  - [x] - Deve desenhar mãos na tela e fazer com que elementos em segundo plano continuem sendo clicáveis 🙌
  - [x] - Deve disparar scroll up quando usar a palma das mãos abertas 🖐
  - [x] - Deve disparar scroll down quando usar a palma das mãos fechadas ✊
  - [x] - Deve disparar click no elemento mais próximo quando usar gesto de pinça 🤏🏻
  - [x] - Ao mover elementos na tela, deve disparar evento **:hover** em elementos em contexto

- Video Player
  - [x] - Deve ser possivel de reproduzir ou pausar videos com o piscar de olhos 😁
  - [x] - Todo processamento de Machine Learning deve ser feito via Web worker

### Referências:

- Acessar as [Referências](./referencias.md)

### FAQ

- browser-sync está lançando erros no Windows e nunca inicializa:
  - Solução: Trocar o browser-sync pelo http-server.
    1. instale o **http-server** com `npm i -D http-server`
    2. no package.json apague todo o comando do `browser-sync` e substitua por `npx http-server .`
    3. agora o projeto vai estar executando na :8080 então vá no navegador e tente acessar o http://localhost:8080/
       A unica coisa, é que o projeto não vai reiniciar quando voce alterar algum código, vai precisar dar um F5 na página toda vez que alterar algo

### Créditos ao Layout

- Interface baseada no projeto [Streaming Service](https://codepen.io/Gunnarhawk/pen/vYJEwoM) de [gunnarhawk](https://github.com/Gunnarhawk)
