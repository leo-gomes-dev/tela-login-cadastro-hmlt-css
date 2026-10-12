# 📝 Desafio Prático: Tela de Login e Cadastro

Bem-vindos ao seu desafio prático de **HTML** e **CSS**! Aqui você vai aplicar o que aprendeu para estruturar e estilizar uma página web real: uma interface contendo um formulário de **Login** e um de **Cadastro**.

Este repositório foi criado para servir de guia. Abaixo, você encontrará as instruções passo a passo para realizar o exercício e publicar seu projeto no GitHub.

---

## 🎯 Objetivo do Exercício
Criar uma página web simples, limpa e responsiva que contenha:
1. Uma seção/formulário para **Login** (Entrar).
2. Uma seção/formulário para **Cadastro** (Criar Conta).
3. Estilização organizada utilizando um arquivo CSS externo (`style.css`).

---

## 📂 Estrutura de Arquivos Recomendada
Para manter seu projeto organizado, crie os arquivos exatamente nesta estrutura dentro da sua pasta de trabalho:

```text
meu-projeto-login/
│
├── index.html   # Aqui fica toda a estrutura da página
├── style.css    # Aqui fica toda a estilização e visual
└── README.md    # Este arquivo com as instruções
```

---

## 🚀 Passo a Passo para Realizar o Desafio

### Passo 1: Clonar ou Criar a Pasta do Projeto
1. Crie uma pasta no seu computador com o nome `desafio-login-cadastro`.
2. Abra essa pasta no seu editor de código (como o **VS Code**).

### Passo 2: Criar a Estrutura HTML (`index.html`)
1. Crie um arquivo chamado `index.html`.
2. Comece com a estrutura básica do HTML5 (dica no VS Code: digite `!` e aperte `Enter`).
3. Altere o título da página no `<title>` para "Login e Cadastro".
4. Dentro da tag `<body>`, crie um contêiner principal (`<main>` ou `<div class="container">`) para envolver os dois formulários.
5. Crie as duas seções utilizando as tags apropriadas:
   * Use `<form>` para os formulários.
   * Use `<input>` para os campos de texto (e-mail, senha, nome).
   * Use `<button>` para os botões de envio.
   * Use `<label>` para identificar cada campo.

### Passo 3: Criar o Visual com CSS (`style.css`)
1. Crie um arquivo chamado `style.css` na mesma pasta.
2. **Não se esqueça de linkar o CSS no HTML!** Adicione a tag `<link rel="stylesheet" href="style.css">` dentro do `<head>` do seu `index.html`.
3. Comece resetando as margens básicas:
   ```css
   * {
       margin: 0;
       padding: 0;
       box-sizing: border-box;
   }
   ```
4. Estilize o `body` para centralizar os formulários na tela (uma boa dica é usar `display: flex;` e `justify-content: center;`).
5. Adicione cores de fundo, bordas arredondadas nos botões (`border-radius`) e espaçamentos internos (`padding`) para deixar o visual agradável e limpo.

### Passo 4: Testar no Navegador
1. Abra o arquivo `index.html` no seu navegador de internet para ver como está ficando.
2. Use a extensão **Live Server** no VS Code se quiser ver as atualizações em tempo real toda vez que salvar o arquivo.

---

## 📤 Como Enviar para o GitHub

Depois de terminar o código, siga estes passos para colocar seu projeto no GitHub e compartilhar seu link:

1. Abra o seu perfil no [GitHub](https://github.com).
2. Clique no botão **New** (Novo) para criar um novo repositório.
3. Dê o nome de `desafio-login-html-css` e clique em **Create repository**.
4. No seu computador, abra o terminal na pasta do projeto e digite os comandos:
   ```bash
   git init
   git add .
   git commit -m "feat: estrutura e estilo da pagina de login e cadastro"
   git branch -M main
   git remote add origin SEU_LINK_DO_REPOSITORIO_AQUI
   git push -u origin main
   ```
5. *(Opcional)* Ative o **GitHub Pages** nas configurações do repositório (`Settings > Pages`) para que todos possam ver sua página rodando ao vivo!

---

## 💡 Dicas de Ouro para Iniciantes
* **Atenção aos nomes das classes:** Use nomes fáceis de lembrar no HTML (`class="btn-enviar"`, `class="campo-input"`) para conseguir puxar corretamente no CSS.
* **Cuidado com as tags de fechamento:** Lembre-se de verificar se abriu e fechou todas as tags corretamente (`<div> ... </div>`).
* **Erros de digitação:** Se o estilo não estiver aparecendo, verifique se a palavra no CSS está escrita exatamente igual à classe do HTML.

Boa sorte e excelente código! 🚀
