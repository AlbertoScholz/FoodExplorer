# FoodExplorer

Food Explorer - Rocketseat Explorer rocket

Este é o resultado do desafio final do Explorer, o Food Explorer.
Nele realizei a criação do FrontEnd e do BackEnd completo da aplicação.
computer Sobre

O Food Explorer é uma aplicação web de um restaurante. Após se cadastrar na plataforma o usuário estará apto a criar os pedidos e acompanhar o status dele. Há ainda uma customização de perfil, filtragem de favoritos, campo de busca e seção de contato com o restaurante. O carrinho é 100% funcional e o usuário pode escolher entre 2 formas de pagamento (cartão ou Pix). O Administrador terá a capacidade de criar/editar/remover os pratos da forma que desejar. Ele poderá ainda alterar o status dos pedidos, de acordo com a linha de preparo dos mesmos na cozinha. Este status será imediatamente atualizado na tela dos consumidores. O projeto conta com diversos "extras" que adicionei, como a possibilidade de mudança de tema da página, customização do perfil do usuário(avatar, nome e senha), conta ainda com diversos efeitos visuais e o mais importante de tudo: É responsivo para a utilização em diversos tipos de dispositivos!

Este repositório contém os dados do Frontend da minha aplicação em React.js e do BackEnd em Node.js.
art Layout

A página inicial em formato desktop é vista na imagem abaixo:

foodexplorer vercel app_

foodexplorer vercel app_ (1)
hammer_and_wrench Tecnologias

As seguintes tecnologias foram empregadas na criação deste projeto:

    ReactJs
    Node.js
    Javascript
    Vite
    Express
    Nodemon
    SQLite
    Knex
    BCryptjs
    JSON Web Token
    Multer
    CORS
    Axios
    Styled Components
    React Icons
    Swiper
    React Router Dom

rocket Como utilizar

Clone o projeto para o local desejado em seu computador.

$ git clone git@github.com:andreviapiana/Food-Explorer.git

construction Executando o BackEnd

# No BackEnd insira uma porta e um secret no arquivo .env vazio
  AUTH_SECRET=
  PORT=

# Navegue até o diretório do BackEnd
$ cd food-explorer-backend

# Instale as dependências necessárias
$ npm install

# Agora inicie o servidor do BackEnd
$ npm run dev

computer Executando o FrontEnd

# Navegue até o diretório do FrontEnd
$ cd food-explorer-frontend

# Instale as dependências necessárias
$ npm install

# Agora inicie o servidor do FrontEnd
$ npm run dev

# O terminal irá exibir o endereço local onde a aplicação está sendo executada. Basta digitar o mesmo endereço em seu navegador preferido. O endereço usado na criação do projeto foi este:

  http://localhost:5173/

key Quer ver como a aplicação funciona vista pelo Admin? Use a conta a seguir:

  e-mail: admin@foodexplorer.com
  senha: 123456

Este BackEnd foi hospedado diretamente no Render. Já o Frontend foi hospedado diretamente no Netlify.

Obs.: Por estar hospedado em um serviço gratuito, o BackEnd "hiberna" após 15 minutos sem utilização.
Se você está tentando acessar o site e o BackEnd não responde, apenas aguarde, pois ele estará "inicializando" os serviços.
Esta etapa poderá demorar até 1 minuto, dependendo da carga nos servidores do Render.

O resultado FINAL pode ser visto aqui
