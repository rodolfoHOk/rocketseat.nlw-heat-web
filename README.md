# 🚀 Front-End ReactJs do NLW-07 HEAT - RocketSeat 🚀

## 👨‍💻 Tecnologias utilizadas 👩‍💻

- Javascript (Linguagem programação)
- Typescript (Tipagem Javascript)
- Vite (Front-end build tool)
- ReactJS (Biblioteca Javascript para criação de interfaces)
- REST (Arquitetura)
- Oauth2 (Autenticação)
- Socket.IO Client (Web socket - Comunicação em tempo-real)

### 🗃️ Bibliotecas utilizadas 📚

- axios : HTTP client
- react : biblioteca criação de interfaces
- react-dom : extensão do ReactJs para manipulação do DOM
- react-icons : ícones para ReactJs
- sass : pré-processador para css
- socket.io-client : cliente do Socket IO para comunicação em tempo-real
- typescript (dev) : adiciona tipagem para javascript
- vite (dev) : front-end build tool

## 🔐 Resumo do fluxo de autenticação Oauth 🚫

- Solicitar login ao github ao clicar no botão de Login com github : https://github.com/login/oauth/authorize?scope=user&client_id=id_do_client
- Autorizar o acesso as informações do usuário do github e inserir as credenciais do github quando for solicitado.
- Pegar o código (code) enviado pelo github na url de Callback (http://localhost:3000/)
- Enviar uma solicitação de login ao back-end enviando o código do github no corpo da requisição (code)
- Como resposta da requisição recebe-se um token para acesso aos recursos e as informações do usuário
- Guardar o token o localStorage
- Inserir o token de acesso no cabeçalho das requisições
- Guardar as informações do usuário em um estado

## 🖇️ Utilização resumida do Socket IO client no app 🔗

- criar um web socket client para um determinado servidor web (método io())
- criar escuta para uma determinada ação emitida pelo servidor (método on())
- a escuta executa uma ação no app (no caso guarda a informação emitida em um estado)

## 🖼️ Imagens do projeto 👀

<img src="https://raw.githubusercontent.com/rodolfoHOk/portfolio-img/main/images/nlw-heat-web-01.png" alt="NLW HEAT Img1" width="450"/>

<img src="https://raw.githubusercontent.com/rodolfoHOk/portfolio-img/main/images/nlw-heat-web-02.png" alt="NLW HEAT Img2" width="450"/>

## ⚙️ Link para o projeto do Back-End no Github 🗄️

https://github.com/rodolfoHOk/nlw-heat-node
