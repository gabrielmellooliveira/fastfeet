<h1 align="center">
  FastFeet
</h1>

### 📜 Sobre o projeto
Um projeto sobre um serviço de gestão e acompanhamento de encomendas para uma transportadora fictícia.

Construído com as tecnologias mais populares do mundo Javascript, este repositório contem uma API REST (Node.js) como backend, uma aplicação em ReactJS como frontend e um app mobile em React Native.

A aplicação em **Node.js** (backend) é uma **API REST** escrita em **Node.JS** que serve dados tanto ao frontend quanto ao mobile. Possuí integração com o **Sentry** para monitoramento de erros em tempo real.

A aplicação em **ReactJS** (frontend) é para o administrador **cadastrar destinatários, entregadores e encomendas**. Assim podendo direcionar e fazer gestão das entregas e outros registros.

A aplicação em **React Native** é para o entregador visulizar as entregas e trabalhar encima delas. Podendo filtrar entre pendentes e entregues, cadastrar problemas que ocorreram durante a entrega e confirmar a entrega enviando uma foto da assinatura.

### Administrador Padrão
 - Login: admin@fastfeet.com
 - Senha: 123456

### 🔽 Requisitos
1. Ter o **NodeJs** e o **Yarn** instalado
2. Ter instâncias do **Redis** e **PostgreSQL** em execução
3. Um dispositivo ou emulador **Android** conectado ao computador
4. **Reactotron** rodando na porta 9090 (**Opcional**)

### :rocket: Começando
1. ``git clone https://github.com/gabrielmellooliveira/fastfeet``
2. ``cd fastfeet``

### :rocket: Iniciando com o backend
1. ``cd backend``
2. ``yarn``
3. ``Crie o arquivo .env com base no .env.example``
4. ``yarn sequelize db:migrate``
5. ``yarn sequelize db:seed:all``
6. ``yarn dev``

### 💻 Iniciando com o Front-end 
1. ``cd frontend``
2. ``yarn``
3. ``yarn start``

### 📱 Iniciando com o Mobile (Apenas Android)
1. ``cd mobile``
2. ``yarn``
3. ``adb reverse tcp:9090 tcp:9090 (Reactotron)``
4. ``adb reverse tcp:3333 tcp:3333``
5. ``react-native start``
6. ``react-native run-android``

<hr>
<p align="center"> Gabriel Mello </p>
