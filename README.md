# Meu Primeiro App - Tabuleiro de Damas

Este projeto é um exercício solicitado pelo professor, onde será exibido um tabuleiro de damas na rota `/exercicioTabuleiro`.

## 🚀 Tecnologias Utilizadas

- **Next.js** - Framework para React
- **JavaScript** - Linguagem de programação
- **CSS** - Estilização do tabuleiro

## 📌 Como rodar o projeto

### 1️⃣ Clonar o repositório

```sh
 git clone https://github.com/mtsSAraujo/ExercicioTabuleiroJS.git
```

### 2️⃣ Acessar a pasta do projeto
```sh
cd ExercicioTabuleiroJS/exercicio/meu-projeto
```

### 3️⃣ Instalar as dependências

```sh
npm install
```

### 4️⃣ Rodar o servidor de desenvolvimento

```sh
npm run dev
```

### 5️⃣ Acessar o projeto no navegador

Após rodar o servidor, acesse:
```
http://localhost:3000/exercicioTabuleiro
```
para visualizar o tabuleiro de damas.

## 📂 Estrutura do Projeto
```
ExercicioTabuleiroJS/exercicio/meu-projeto/
│-- app/
│   ├── exercicioTabuleiro/  # Página do tabuleiro
│-- public/                  # Arquivos estáticos
│-- .next/                   # Build do Next.js
│-- node_modules/            # Dependências instaladas
│-- .gitignore               # Arquivos ignorados pelo Git
│-- eslint.config.mjs        # Configuração do ESLint
│-- jsconfig.json            # Configuração do JavaScript
│-- next.config.mjs          # Configuração do Next.js
│-- package.json             # Dependências e scripts
│-- README.md                # Documentação do projeto
```

## 🛠️ Possíveis Problemas

### Next.js não reconhecido como comando
Se ao rodar `npm run dev` aparecer um erro dizendo que `next` não é um comando reconhecido, tente rodar:

```sh
npm install next
```

e então tente rodar o projeto novamente.

---

Este é um exercício acadêmico e pode ser expandido no futuro! 🚀

