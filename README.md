<h1 align="center">NLW Heat</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-backend">Executando backend</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-frontend">Executando frontend</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-mobile">Executando mobile</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=8257E5&labelColor=000000">
  <img src="https://img.shields.io/static/v1?label=NLW&message=Heat&color=8257E5&labelColor=000000" alt="NLW Heat" />
</p>

## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)
- [Expo](https://docs.expo.dev/)

## 🚀 Backend

> Obs.: Nesse projeto temos autenticação via OAuth com o GitHub
  
- Clone o repositório e acesse a pasta `server`
- Faça uma copia do arquivo `.env.example` para `.env` e preencha com as suas credenciais do GitHub;
- Instale as dependências com `yarn`;
- Executa as migrations com `yarn prisma migrate dev`;
- Pode ser necessário executar o comando `yarn prisma generate`;
- Inicie o servidor com `yarn dev`;

## 🚀 Frontend

- Clone o repositório e acesse a pasta `web`
- Instale as dependências com `yarn`;
- Inicie o servidor com `yarn dev`;

## 🚀 Mobile
> Obs.: Nesse projeto utilizamos Expo, certifique que ele esteja instalado
> 
- Clone o repositório e acesse a pasta `mobile`
- Instale as dependências com `yarn`;
- Inicie a aplicação com `expo start`;

A aplicação pode ser acessada em [`localhost:4000`](http://localhost:4000).

## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito com ♥ by Rocketseat 👋🏻 &nbsp;[Participe da nossa comunidade!](https://discordapp.com/invite/gCRAFhc)
