### 📒 Trabalhando com arquivos Vue e rodando o servidor

---

#### 📁 1. Criar um novo componente `.vue`

Dentro da pasta `src/components`, crie um novo arquivo, por exemplo:  
`Navbar.vue`

`<template>   <nav>     <h1>Minha Navbar 🌸</h1>   </nav> </template>  <script> export default {   name: 'Navbar' } </script>  <style scoped> nav {   background-color: #f2f2f2;   padding: 10px; } </style>`

---

#### 🌐 2. Usar o componente no `App.vue`

`<template>   <div>     <Navbar />     <router-view />   </div> </template>  <script> import Navbar from './components/Navbar.vue'  export default {   components: {     Navbar   } } </script>`

---

#### ▶️ 3. Iniciar o servidor pela primeira vez

Dentro da pasta do projeto:

`npm run serve   # Se o projeto foi criado com Vue CLI # ou npm run dev     # Se o projeto foi criado com Vite`

➡️ Acesse no navegador: [http://localhost:8080](http://localhost:8080)

---

#### 🔁 4. Reiniciar o servidor (quando o terminal for fechado)

Se o terminal for fechado ou você desligar o PC, basta abrir novamente a pasta do projeto no terminal e rodar:

`npm run serve   # ou npm run dev`

---

#### 🔍 Dicas rápidas

- Se o componente não aparecer, verifique se o nome e caminho do import estão corretos.
    
- Sempre salve o arquivo depois de editar (o servidor recarrega automaticamente).
    
- Evite espaços ou letras maiúsculas nos nomes de arquivos para evitar erros.