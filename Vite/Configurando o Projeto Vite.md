# Configurando o Projeto Vite

A configuração padrão está em `vite.config.js`. Você pode editar este arquivo para adicionar plugins ou modificar comportamentos do build e dev server.

Exemplo básico de configuração:

```js
import { defineConfig } from 'vite'
import vue from '@vitejs/plugin-vue'

export default defineConfig({
  plugins: [vue()],
})
```
