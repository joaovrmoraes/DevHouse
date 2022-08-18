<h1 align="center"> DevHouse </h1>

    Projeto de API desenvolvida no curso: 
    # Curso completo de APIs com Nodejs, Express + MongoDB, SQL ministrado por Matheus Fraga.
  
  . Usuario: Poderá fazer o cadastro na apliação via e-mail e tambem realizar o login via e-mail.
   O usuario deve poder reservar alguma casa desde que não seja suas próprias casas  ou reserva casas com status indisponivel.
   Poderá cancelar sua reserva há qualquer momento.
   
 . Houses: Usuario logado poderá cadastar uma nova casa, editar ou excluir suas casas quando quiser. Casas cadastradas devem conter uma Foto de capa, descrição, localização, preço da diária e o status(Disponivel ou Indisponivel).
 
### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/) 
- [Express](https://expressjs.com/pt-br/)
- [MongoDB](https://www.mongodb.com/atlas/database)
 
### Comandos 
 
```
yarn init -y
yarn add express
yarn add sucrase nodemon -D
yarn add mongoose
yarn add multer // pra trabalhar com multipart (insomnia)
yarn add cors // pra deixar nossa api publica e qualquer um consumir
yarn add yup // pra verificar validações (ex: usuário não conseguir cadastrar uma casa sem todos parâmetros)
```
