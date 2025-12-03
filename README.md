# Portal de Notícias PBE (Programação Back-End)

**Raissa dos Santos Fernandes**

## 📝 Descrição

Este projeto é um **Portal de Notícias Dinâmico** desenvolvido para a disciplina de Programação Back-End (PBE). O objetivo central foi **integrar um layout estático** **com uma API real de notícias** (NewsAPI), transformando-o em uma **aplicação dinâmica** utilizando a stack Node.js.

A aplicação utiliza **Express** para configurar o servidor **EJS** como motor de visualização para renderizar as notícias dinamicamente em formato de loop, e **Axios** para o consumo da API externa.A **segurança** é priorizada com a leitura da API Key através de variáveis de ambiente (`.env`), evitando exposição de credenciais.

## ▶️ Como Rodar o Projeto

Para executar este projeto localmente, siga os passos abaixo:

### 1. Preparação do Ambiente

Crie o arquivo `.env` na raiz do projeto (junto ao `app.js`) e adicione sua chave de API e a porta:

### 2. Instalação de Dependências

Abra o terminal na pasta raiz do projeto (`portal-backend/`) e execute os comandos:

```bash
# Inicializa o package.json
npm init -y

# Instala o servidor (express), o motor de HTML (ejs), o conector de API (axios) e o gerenciador de variáveis de ambiente (dotenv) 
npm install express ejs axios dotenv

**Lembre-se de substituir `Raissa dos Santos Fernandes` antes de enviar.**

Essa documentação atende aos critérios de avaliação que exigem o `README.md` preenchido com a descrição do projeto e dados do aluno.
```
---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Função no Projeto |
| :--- | :--- |
| **Node.js** | Ambiente de execução JavaScript no servidor. |
| **Express** | Framework utilizado para criar e gerenciar o servidor web. |
| **EJS** | Motor de visualização para integrar o HTML com dados dinâmicos do Back-End. |
| **Axios** | Cliente HTTP para fazer as requisições à NewsAPI. |
| **Dotenv** | Gerenciador de variáveis de ambiente para o arquivo `.env`. |
| **HTML5 & CSS3** | Estrutura e estilização do Frontend. |

---

## 📂 Estrutura do Projeto

| Estrutura de Pastas | Descrição |
| :--- | :--- |
| `portal-backend/` | Pasta raiz do seu projeto Node.js. |
| ├── `node_modules/` | Pasta criada após `npm install` (Ignorada pelo Git). |
| ├── `public/` | Contém arquivos estáticos.  |
| │   ├── `css/` | Contém o arquivo `style.css` (seu CSS).  |
| │   └── `img/` | Contém `padrao.jpg` (imagem padrão).  |
| ├── `views/` |Contém os templates EJS.  |
| │   └── `index.ejs` | Seu template de visualização principal.  |
| ├── `.env` | Arquivo com credenciais (API Key e Porta).  |
| ├── `.gitignore` | Configuração para não enviar `node_modules` e `.env`.  |
| ├── `app.js` | Seu servidor Node.js principal.  |
| └── `package.json` | Configurações e dependências do projeto.  |
