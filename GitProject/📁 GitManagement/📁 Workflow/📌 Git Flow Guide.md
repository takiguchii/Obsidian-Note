
Nosso projeto usa um modelo baseado em **Git Flow**, simplificado para 3 principais branches:

---

## 🌿 Principais branches

- `main` → versão estável e pronta para produção
- `develop` → branch de integração para todas as features
- `feature/*` → branches de desenvolvimento de novas funcionalidades

---

## 🔁 Fluxo de trabalho

1. Criar uma branch a partir de `develop`:
    `git checkout develop`
	`git checkout -b feat/backend/ale/barcode-service`

2. Trabalhar na feature e fazer commits

3. Quando finalizar:
	- Fazer push da branch
	- Criar Pull Request para `develop`

4. Após testes e revisão, mergear para `develop`

5. A cada entrega estável:
	- Criar Pull Request de `develop` para `main`
	- Fazer `tag` da versão se necessário

---

## 📦 Extras

- Branches de hotfix partem de `main` e são mergeadas tanto em `main` quanto em `develop`
- Nunca trabalhar diretamente na `main` ou `develop`!