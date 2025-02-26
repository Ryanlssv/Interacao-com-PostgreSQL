# Interação com um Banco de Dados PostgreSQL

Este projeto é um exemplo prático de como construir uma aplicação simples que interage com um banco de dados PostgreSQL, utilizando tecnologias como **HTML**, **CSS**, **JavaScript** (frontend) e **Node.js** com **Express** (backend).

## 🛠 Tecnologias Utilizadas

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express  
- **Banco de Dados**: PostgreSQL  

---

## 📋 Estrutura do Projeto

### 1. Frontend (HTML, CSS, JavaScript)
O frontend é responsável pela interface com o usuário.

- **HTML**: Define a estrutura da página, incluindo um formulário para adicionar documentos e uma tabela para exibi-los.
- **CSS**: Cuida da estilização da página, como cores, fontes e layout.
- **JavaScript**: Faz chamadas ao backend para buscar, adicionar ou excluir documentos no banco de dados.

### 2. Backend (Node.js + Express)
O backend gerencia as interações entre o frontend e o banco de dados. Ele fornece as rotas para:
- **GET**: Buscar todos os documentos armazenados.
- **POST**: Adicionar um novo documento.
- **DELETE**: Excluir um documento pelo ID.

### 3. Banco de Dados (PostgreSQL)
A aplicação utiliza um banco de dados PostgreSQL com uma tabela chamada `documents`, contendo:
- **id**: Identificador único.
- **title**: Título do documento.
- **created_at**: Data de criação do documento.

---

## ⚙️ Como Funciona

1. **Fluxo de Interação**:
   - O frontend envia requisições ao backend para buscar, adicionar ou excluir documentos.
   - O backend realiza operações no banco de dados e retorna os resultados para o frontend.
   - O frontend exibe os resultados na interface do usuário.

2. **Passo a Passo**:
   - Quando a página é carregada, o JavaScript busca os documentos existentes no banco de dados e os exibe na tabela.
   - Ao adicionar um novo documento, o formulário envia os dados ao backend, que os salva no banco de dados.
   - A tabela é atualizada automaticamente com os novos dados.

---

## 🚀 Como Rodar a Aplicação

### Pré-requisitos
- Node.js instalado.
- PostgreSQL configurado.

