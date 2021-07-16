# School File Manager
## Projeto Inserido na Unidade Curricular Processamento e Representação de Raciocínio 2020/2021
### [Mestrado Integrado em Engenharia Informática na Universidade do Minho](https://miei.di.uminho.pt/)


O **School File Manager** é uma applicação web que pretende facilitar a troca de documentos num contexto escolar, seja teses, artigos, resumos ou exercícios. É constituída por 3 serviços, um serviço API REST, uma interface e um serviço de autenticação. Para que a segurança seja salvaguardada, são utilizadas ferramentas como o [**Json Web Token**](https://jwt.io) e [**OpenSSL**](https://www.openssl.org/). No desenvolvimento da interface utilizamos a ferramenta [**Nicepage**](https://nicepage.com/) e o website [**W3Schools**](https://www.w3schools.com/), a implementação foi efetuada em [**Node.js**](https://nodejs.org/en/). Para persistência de dados utilizamos uma base de dados não relacional implementada em [**MongoDB**](https://www.mongodb.com/)

<p align="center">
  <img width="200" height="200" src="https://github.com/luis1ribeiro/School-File-Manager/blob/main/Interface/public/images/login.png">
</p>

Para correr executar a aplicação é necessário ter instalado o [**NPM**](https://www.npmjs.com/). Basta pelo terminal basta fazer:
```cmd
 npm install
 npm start
```
Em cada uma das diretorias seguindo a seguinte ordem: Authorization-server -> api-server -> Interface.

### [Relatório](https://github.com/luis1ribeiro/School-File-Manager/blob/main/report.pdf)

## Development Team

* [Diogo Pereira](https://github.com/dpereira7)
* [Francisco Lopes](https://github.com/chico2911)
* [Luís Ribeiro](https://github.com/luis1ribeiro)
* [Gonçalo Pinto](https://github.com/GRP99)

## Agradecimentos

Queremos agradecer ao docente por toda a disponibidade, motivação e ajuda que nos facultou a desenvolver o projeto. Foi frucal a sua orientação para a realização do mesmo.