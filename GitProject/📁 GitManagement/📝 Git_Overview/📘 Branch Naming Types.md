Esta nota tem como objetivo documentar os **prefixos usados no nome das branches**, indicando o tipo de tarefa que está sendo realizada.

Utilizamos a seguinte estrutura básica:

`<type>/<area>/<dev-name>/<description>`

---

### 📂 Tipos de prefixos (type)

|Prefixo|Significado|Quando usar|
|---|---|---|
|`feat`|_Feature_ – Nova funcionalidade|Criar algo novo no sistema, como uma tela ou endpoint novo|
|`fix`|_Fix_ – Correção de bug|Corrigir comportamento incorreto de algo que já existe|
|`mod`|_Modification_ – Alteração em algo existente|Ajustar lógica, refatorar código, mudar textos|
|`css`|Estilização visual|Trabalhar no layout, cores, padding, responsividade|
|`test`|Implementação ou ajuste de testes|Criar ou alterar testes automatizados|
|`doc`|Documentação|Atualizar arquivos `.md`, instruções, README etc|
|`hotfix`|Correção urgente diretamente na branch principal|Situações críticas que precisam ser resolvidas imediatamente|
|`refactor`|Reorganização de código, sem mudar funcionalidade|Melhorar performance ou legibilidade sem mudar o que já faz|

---

### 📌 Exemplo de uso completo:

`feat/backend/ale/barcode-decoder fix/frontend/raul/camera-freeze css/frontend/kennedy/style-camera-button mod/backend/ale/barcode-validation`