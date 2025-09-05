<div align="center">

  <h1 align="center"><strong>API Fórmula 1 - Node.js + TypeScript</strong></h1>
  <p align="center">
      Uma API simples para consultar equipes e pilotos da Fórmula 1.<br>
      Construída com <b>Node.js</b>, <b>TypeScript</b> e <b>Fastify</b>.
  </p>

</div>

<br />

# 🚀 Tecnologias

- **Node.js** v20+
- **TypeScript**
- **Fastify**
- **@fastify/cors**

# 📦 Endpoints

A API disponibiliza os seguintes endpoints:

- `GET /teams`  
  Retorna a lista de equipes da Fórmula 1.

- `GET /drivers`  
  Retorna a lista de pilotos da Fórmula 1.

- `GET /drivers/:id`  
  Retorna os dados de um piloto pelo seu ID.

# ⚡ Scripts

- `npm run start:dev`: Executa o servidor em modo desenvolvimento.
- `npm run start:watch`: Executa o servidor em modo desenvolvimento com recarga automática.
- `npm run dist`: Compila os arquivos TypeScript para JavaScript na pasta dist.
- `npm run start:dist`: Compila e executa a versão gerada na pasta dist.

# 👨‍💻 Como usar

Você precisa ter [Git](https://git-scm.com), [Node.js v20+](https://nodejs.org/en/) e [NPM v10+](https://nodejs.org/en/) instalados.

```bash
# Clone este repositório
git clone https://github.com/seu-usuario/seu-repo.git

# Entre na pasta do projeto
cd seu-repo

# Instale as dependências
npm install

# Execute o servidor em modo desenvolvimento
npm run start:dev
```

A API estará disponível em [http://localhost:3333](http://localhost:3333).

# Créditos

Ícones por [Pino Lamanna][dribble-icon]

[dribble-icon]: https://dribbble.com/Schakalwal