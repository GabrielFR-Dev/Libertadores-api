# ⚽ Libertadores API

API REST desenvolvida em Node.js para consulta de dados da Copa Libertadores.

## 📌 Status do projeto

🚧 Em desenvolvimento

Atualmente o projeto realiza a conexão com o banco de dados MySQL.
As próximas etapas incluem a criação de rotas para consulta dos dados.

---

## 🎯 Objetivo

Construir uma API capaz de fornecer informações sobre:

* Campeões da Libertadores (2000 - 2022)
* Vice-campeões


---

## 🛠️ Tecnologias utilizadas

* Node.js
* Express
* MySQL
* dotenv

---

## 🔐 Segurança

As credenciais do banco de dados são armazenadas em variáveis de ambiente (`.env`) e não são versionadas no repositório.

---

## ⚙️ Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/libertadores-api.git
```

### 2. Instalar dependências

```bash
npm install
```

### 3. Criar arquivo `.env`

Crie um arquivo `.env` na raiz do projeto com:

```env
DB_HOST=localhost
DB_USER=seu_usuario
DB_PASSWORD=sua_senha
DB_NAME=libertadoresdb
```

### 4. Executar o projeto

```bash
node index.js
```

O servidor será iniciado em:

```
http://localhost:9000
```

---

## 📡 Próximas funcionalidades

* [ ] Rota GET /campeoes
* [ ] Rota GET /vices
* [ ] Filtros por ano
* [ ] Organização em arquitetura MVC

---

## 📚 Aprendizados

Este projeto está sendo desenvolvido com foco em aprendizado de:

* APIs REST
* Integração com banco de dados
* Boas práticas de segurança com `.env`
* Estruturação de backend

---

## 👨‍💻 Autor

Gabriel Ferreira
