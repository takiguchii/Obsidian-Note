### 📒 Instalação do Node.js e Vue.js no Linux (Ubuntu/Debian)

---

#### 🐢 1. Atualizar o sistema (opcional, mas recomendado)

`sudo apt update && sudo apt upgrade`

---

#### 🔧 2. Instalar o Node.js (via NodeSource)

`curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - sudo apt install -y nodejs`

✅ Verificar se o Node e npm foram instalados:

`node -v npm -v`

---

#### 🍃 3. Instalar o Vue CLI (Interface de Linha de Comando do Vue.js)
t
`npm install -g @vue/cli`

✅ Verificar instalação:

`vue --version`

---

#### 🚀 4. Criar um novo projeto Vue.js

`vue create nome-do-projeto`

> Dica: Pode usar as setinhas e o espaço pra escolher o que quer incluir no projeto (Ex: Babel, Router, etc).
n
---

#### 🧪 5. Rodar o projeto localmente

`cd nome-do-projeto npm run serve`

➡️ Acesse no navegador: [http://localhost:8080](http://localhost:8080)

---

#### 🌱 Alternativa moderna: Usando Vite (mais leve e rápido)

`npm create vite@latest cd nome-do-projeto npm install npm run dev`

---

#### 💬 Notas finais

- O Vue pode ser usado com ou sem o CLI, mas o CLI facilita muito o desenvolvimento.
    
- Mantenha o Node.js sempre atualizado se possível.
    
- Se você estiver com problemas de permissão, tente usar `sudo`, mas com cuidado.