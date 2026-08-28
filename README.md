# 💰 PocketCoin API

API REST desenvolvida em **TypeScript e Node.js** para disponibilização de serviços relacionados a moedas, conversão de valores e integração de dados.

O projeto demonstra a construção de uma camada de backend responsável por receber requisições, processar informações, integrar serviços externos e disponibilizar dados por meio de endpoints REST.

## 🎯 Objetivo

Desenvolver uma API capaz de centralizar operações relacionadas a moedas e fornecer uma estrutura organizada para consumo e integração com aplicações clientes.

## 🏗️ Arquitetura

O projeto utiliza uma arquitetura baseada em:

```text
Aplicação cliente
       ↓
    API REST
       ↓
   Controllers
       ↓
     Services
       ↓
     Models
       ↓
    MongoDB
```

Também são utilizadas integrações com serviços externos para obtenção de informações.

## 🔄 Integração de dados

O projeto trabalha com o fluxo:

```text
Fonte externa
      ↓
Requisição HTTP
      ↓
Processamento
      ↓
Persistência / Cache
      ↓
API REST
      ↓
Aplicação cliente
```

Essa estrutura demonstra conceitos importantes de **integração de dados e desenvolvimento de serviços backend**.

## 🛠️ Tecnologias

* **TypeScript**
* **Node.js**
* **Express**
* **MongoDB**
* **Mongoose**
* **Axios**
* **JWT**
* **Node Cache**
* **Swagger**

## 🔐 Recursos

* API REST
* Autenticação
* Persistência em MongoDB
* Integração com APIs externas
* Cache de informações
* Documentação da API
* Estrutura modular de backend

## 📖 Documentação da API

A API utiliza **Swagger** para documentação e consulta dos endpoints disponíveis.

Após executar a aplicação, a documentação pode ser acessada pela rota configurada no projeto.

## 🔎 Competências demonstradas

`Backend` · `APIs REST` · `Integração de Dados` · `TypeScript` · `Node.js` · `MongoDB` · `Mongoose` · `APIs Externas` · `Swagger`

## 🚀 Como executar

### 1. Instalar dependências

```bash
npm install
```

### 2. Configurar variáveis de ambiente

Crie um arquivo `.env` com as configurações necessárias para o ambiente.

### 3. Executar em desenvolvimento

```bash
npm run dev
```

### 4. Build

```bash
npm run build
```

### 5. Executar produção

```bash
npm start
```

## 🎓 Contexto

Projeto desenvolvido para aplicação prática de conceitos de **backend, APIs, bancos de dados e integração de informações**, utilizando TypeScript e Node.js.
