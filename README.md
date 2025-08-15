# 💖 Site Romântico – Para Catiça

Este projeto foi criado como um presente especial para Catiça, com o objetivo de oferecer um espaço romântico e aconchegante para ler, criar e compartilhar histórias de romance, drama e fantasia.

## ✨ Funcionalidades

- **Página inicial personalizada:** Fundo azul escuro e mensagem romântica especial.
- **Login/Cadastro:** Sistema simples por e-mail, nome e senha.
- **Leitura de livros e fanfics:** Navegação capítulo a capítulo, leitura confortável, fundo escuro e detalhes dourados.
- **Criação de histórias:** Editor básico para escrever e publicar novos romances, dramas e fanfics.
- **Banco de dados:** Armazena usuários, histórias e capítulos.
- **Layout responsivo:** Perfeito para celulares e computadores.
- **Paleta de cores:** Azul escuro, branco e dourado.

## 🛠️ Tecnologias Utilizadas

- **Front-end:** HTML, CSS, JavaScript (com EJS para templates)
- **Back-end:** Node.js com Express
- **Banco de dados:** SQLite
- **Hospedagem:** Compatível com Vercel ou servidor próprio

## 📂 Estrutura de Pastas

```
/public         # arquivos estáticos (css, imagens)
/views          # templates das páginas
/routes         # rotas do Express
/database       # banco de dados SQLite
/app.js         # servidor principal
/README.md      # este arquivo
```

## 🚀 Como executar localmente

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/Itadori444/para-mor.git
   cd para-mor
   ```

2. **Instalar dependências:**
   ```bash
   npm install
   ```

3. **Criar o banco de dados:**
   ```bash
   mkdir database
   sqlite3 ./database/site.db < database/schema.sql
   node database/seed.js
   ```

4. **Iniciar o servidor:**
   ```bash
   node app.js
   ```

5. **Acessar no navegador:**
   ```
   http://localhost:3000
   ```

## 📖 História especial

O site já vem com a história “O se tivesse encontrado o lugar certo” dedicada à Catiça.  
Outras histórias de romance, drama e fantasia também estão disponíveis para leitura e inspiração.

## 🎁 Dedicatória

> “Algumas histórias são tão raras que merecem ser vividas até a última linha — e a nossa ainda está apenas começando.”

Feito com amor por Itadori444 💗

---
