### 📒 Vue.js — Introdução e Conceitos Básicos

#### 🧩 O que é o Vue.js?

Vue.js é um **framework JavaScript progressivo** para construir interfaces de usuário. Ele é conhecido por ser **leve, fácil de aprender** e extremamente **flexível**, permitindo que você use aos poucos ou em aplicações completas com roteamento, estado global, etc.

---

#### ⚙️ Principais conceitos

##### 1. **Componentes**

- Tudo no Vue é dividido em **componentes** reutilizáveis.
    
- Cada componente é geralmente representado por um arquivo `.vue`.
    
- Exemplo básico:
    
    vue
    
    `<template>   <h1>Olá, Vue!</h1> </template>  <script> export default {   name: 'MeuComponente' } </script>`
    

---

##### 2. **Reatividade**

- Vue usa um sistema de reatividade para **atualizar automaticamente** o DOM quando os dados mudam.
    
- Usamos `data()` para declarar variáveis reativas:
    
    js
    
    `data() {   return {     mensagem: 'Olá, mundo!'   } }`
    

---

##### 3. **Diretivas**

- São palavras especiais com prefixo `v-` que controlam o DOM.
    
- Exemplos:
    
    - `v-if` – renderiza se for verdadeiro.
        
    - `v-for` – faz um loop.
        
    - `v-model` – faz ligação bidirecional com inputs.
        

---

##### 4. **CLI (Vue CLI ou Vite)**

- Ferramentas para iniciar projetos rapidamente.
    
- Comandos comuns:
    
    bash
    
    CopyEdit
    
    `npm install -g @vue/cli       # Instala o Vue CLI vue create meu-projeto        # Cria um projeto npm run serve                 # Roda em modo desenvolvimento`
    
    Ou com Vite:
    
    bash
    
    CopyEdit
    
    `npm create vite@latest        # Cria com Vite npm install                   # Instala dependências npm run dev                   # Roda o projeto`
    

---

##### 5. **Roteamento (Vue Router)**

- Permite navegar entre páginas sem recarregar a página.
    
- Cada rota aponta para um componente.
    

---

##### 6. **Gerenciamento de Estado (Pinia ou Vuex)**

- Usado para compartilhar dados entre componentes de forma mais estruturada.
    

---

#### 💡 Dicas

- Comece com componentes pequenos e simples.
    
- Use a CLI ou Vite para facilitar o desenvolvimento.
    
- Mantenha o projeto modular (separe os arquivos).
    
- Aproveite a documentação oficial: [https://vuejs.org](https://vuejs.org)