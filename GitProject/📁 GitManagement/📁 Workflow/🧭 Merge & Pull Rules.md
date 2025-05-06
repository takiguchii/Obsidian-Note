

Regras para manter o repositório limpo, revisado e sem conflitos desnecessários.

---

## 📤 Pull Request

- Sempre que terminar uma task, crie um Pull Request da sua branch para `develop`
- O título do PR deve ser claro:
- 
(feat) Add barcode validation service

---

## 🔍 Revisão

- Pelo menos 1 outro membro do grupo deve revisar o código antes do merge
- Comentários de revisão devem ser respondidos
- Só fazer merge após aprovação

---

## 🔀 Merge

- Sempre usar **merge via PR**, nunca via terminal direto
- Resolver conflitos **antes** do merge
- Preferir **merge commit** (não squash, para manter histórico limpo)

---

## ⚠️ Outras regras

- Atualize sua branch com `develop` antes de criar o PR:
git pull origin develop

- Se a PR for urgente (hotfix), avise o grupo e dê prioridade à revisão