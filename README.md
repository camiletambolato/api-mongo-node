# 📦 API REST - Gerenciamento de Produtos com Node.js e MongoDB

Esta é uma API RESTful desenvolvida com Node.js, Express e MongoDB Atlas para o gerenciamento de um catálogo de produtos.

## 🛠️ Tecnologias Utilizadas

* Node.js
* Express
* MongoDB (driver oficial)
* dotenv

## 📂 Estrutura do Projeto

* api-mongo-node/
  * imagens/
    * image.png
    * image-1.png
    * image-2.png
    * image-3.png
    * image-4.png
    * image-5.png
  * .env
  * .gitignore
  * index.js
  * package.json
  * README.md

## ⚙️ Configuração

### 1. Instalar dependências
```bash
npm install
```

### 2. Configurar o .env
Crie o arquivo `.env` na raiz:
```env
MONGO_URI=mongodb+srv://camiletambolato_db_user:lLRv3sDownGgxkGm@cluster0.m1djrev.mongodb.net/
```

### 3. Iniciar o servidor
```bash
node index.js
```

---

## 🚀 Métodos HTTP e Evidências

### POST
Adiciona um novo produto ao banco de dados (`insertOne`).

![POST](./imagens/image.png)

### PUT
Atualiza os dados de um produto por ID (`updateOne`).

![PUT](./imagens/image-1.png)

### GET
Lista todos os produtos (`find`) ou busca um produto por ID (`findOne`).

![GET](./imagens/image-2.png)

### DELETE
Remove um produto por ID (`deleteOne`).

![DELETE](./imagens/image-3.png)

---