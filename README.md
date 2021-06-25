# Letmeask

# Projeto
Este projeto foi desenvolvido durante a [Next Level Week Together](https://nextlevelweek.com/inscricao/6), evento desenvolvido pela [Rocketseat](https://rocketseat.com.br/), e apresentado dos dias 20 a 27 de Junho de 2021.

O letmeask permite que criadores de conteúdo possam criar salas de Q&A com o seu público.

# Tecnologias

* [Firebase](https://firebase.google.com/)
* [React](https://reactjs.org/)
* [Typescript](https://www.typescriptlang.org/)

# Layout

O layout do projeto pode ser visualizado no link abaixo:

* [Layout](https://www.figma.com/file/u0BQK8rCf2KgzcukdRRCWh/Letmeask/duplicate?node-id=0%3A1)

É necessário que voce tenha uma conta no Figma.

# Como executar

Clone o projeto e acesse a pasta do mesmo.
```
$ git clone https://github.com/thiagosbernardes/letmeask
$ cd letmeask
```
Crie um novo projeto no Firebase e habilite os seguintes serviços:
* Authentication (O método utilizado no projeto foi Google);
* Realtime Database.

Adicione as regras presentes no arquivo database_rules, ao realtime database que você criou no firebase.

Para iniciar, siga os seguintes passos:
```
#baixar e instalar as dependências
$ yarn

#iniciar o projeto
$ yarn start
```
O app poderá ser acessado no seu browser pelo endereço http://localhost:3000.

Lembrando que é necessário possuir uma conta no Firebase e um projeto para disponibilizar os serviços de autenticação e realtime database.