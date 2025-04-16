
# 📦 API REST – Mini Game

Este projeto é uma API REST desenvolvida como parte dos meus estudos sobre Web Services. A  API permite o gerenciamento de itens de um jogo, com suporte completo a operações CRUD (Create, Read, Update, Delete) em um banco de dados MongoDB.

---

## ⚙️ Funcionalidades

- 🔍 **Listar Itens** – Retorna todos os itens cadastrados.
- 📄 **Consultar Item** – Retorna os dados de um item específico via ID.
- ➕ **Criar Item** – Adiciona um novo item ao banco de dados.
- ✏️ **Atualizar Item** – Atualiza as informações de um item existente.
- ❌ **Deletar Item** – Remove um item do banco de dados.

---

## 🛠️ Tecnologias Utilizadas

- **.NET 8.0** – Framework principal para desenvolvimento da API.
- **MongoDB.Driver** – Biblioteca para integração com MongoDB.
- **Swagger (Swashbuckle)** – Interface interativa para documentação e testes.
- **Visual Studio Code** – Ambiente de desenvolvimento utilizado.

---

## 🚀 Como Executar a API

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/API-rest-mini-game.git
cd API-rest-mini-game
```

### 2. Configure o banco de dados

Certifique-se de que o **MongoDB** está instalado e em execução. Atualize as credenciais no arquivo `appsettings.json`:

```json
"MongoDbSettings": {
  "Host": "localhost",
  "Port": "27017",
  "User": "seu_usuario",
  "Password": "sua_senha"
}
```

### 3. Instale as dependências

```bash
dotnet restore
```

### 4. Execute a aplicação

```bash
dotnet run
```

---

## 📌 Requisitos

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download)
- MongoDB instalado e rodando localmente ou em um servidor remoto
