# 💻 Projeto: Labook

[Documentação API](https://documenter.getpostman.com/view/20354712/UzQoTo8T)


## :dart: Requisitos

O LaBook será uma rede social com o objetivo de promover a conexão e interação entre seus mais diversos usuários. Os usuários podem criar posts de dois tipos ("evento" ou "normal"), comentá-los e curti-los também.

### Cadastrar
- Para o cadastro nessa rede social, o usuário deve fornecer seu nome, seu e-mail e uma senha. Além disso, esse endpoint já tem que realizar o login do usuário, fornecendo seu token de autenticação no retorno da requisição.

### Logar
- Para realizar o login, basta informar seu e-mail e a sua senha. O retorno deve conter o token de autenticação do usuário.

### Criar post
- O post deve ser criado, passando-se as informações de: foto, descrição, data de criação e tipo ("normal" ou "evento").

### Buscar um post por id
- Ao passar o id de um post, você deve obter as informações a respeito daquele post

### Fazer amizade
- Criar uma amizade é simples: basta receber o token de autenticação junto com o Id do usuário com o qual se deseja fazer amizade. 
- Uma amizade é uma "relação mútua": quando um usuário vira amigo de outro, esse outro "já é amigo" desse primeiro usuário (ou seja, o segundo usuário não precisa virar amigo do outro depois)

### Desfazer Amizade
- Encerrar uma amizade segue o mesmo fluxo de fazer: com o token de autenticação e o id do usuário, já é possível realizar esse processo.
- Observação: você deve retornar um erro caso o usuário tente desfazer uma amizade com alguém com quem não tem essa amizade registrada no banco!

### Ver todo o Feed 
- O feed é composto por todos os posts dos amigos do usuário logado. Os posts devem ser retornado em ordem de criação: do mais recente ao mais antigo.

### Ver apenas um tipo de post do Feed
- Esse endpoint deve receber um tipo ("normal" ou "evento") e retornar todos os posts que sejam do tipo especificado, não apenas os de amigos. Os posts devem ser retornados em ordem de criação: do mais recente ao mais antigo.

### ⚙️ O que funciona
- Cadastro de novo usuário
- Login 
- Criar post
- Buscar um posto por ID
- Fazer amizade
- Desfazer amizade
- Ver todos os posts de amigos
- Ver apenas um tipo de posto no feed

### ⚙️ O que não funciona
- As funcionalidades abaixo serão implementadas futuramente
- Curtir Post
- Descurtir Post
- Comentar Post

### :computer: Tecnologias
- Node.js
- Typescript
- MYSQL
- Programação Orientada à Objetos
- Express
- Knex
- bcryptjs
- uuid
- jsonwebtoken
- moment




## 👨‍💻 Desenvolvedor:

| [<img src="https://avatars.githubusercontent.com/u/69327864?s=96&v=4" width=115><br><sub>Renan Alencar</sub>](https://github.com/Renan-Ma)
| :---: | 
