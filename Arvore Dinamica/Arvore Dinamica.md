
# 🌳 Árvore Dinâmica em Python

## 📌 O que é?
Uma **árvore dinâmica** é uma estrutura de dados hierárquica onde cada **nó (node)** pode ter **vários filhos**. Ela é chamada de "dinâmica" porque **pode crescer ou mudar** durante a execução do programa (adicionando ou removendo nós).

## 🧠 Conceitos principais:
- **Raiz (root):** o nó principal da árvore.
- **Filho (child):** um nó ligado a outro diretamente acima (pai).
- **Pai (parent):** um nó que possui filhos.
- **Folha (leaf):** um nó que não possui filhos.
- **Subárvore:** uma árvore dentro de outra árvore (ramificação).

---

## 🧱 Implementação Básica

```python
class No:
    def __init__(self, valor):
        self.valor = valor
        self.filhos = []

    def adicionar_filho(self, filho):
        self.filhos.append(filho)

    def mostrar(self, nivel=0):
        print('  ' * nivel + f'- {self.valor}')
        for filho in self.filhos:
            filho.mostrar(nivel + 1)
```

---

## 🌱 Exemplo de Uso

```python
# Criando os nós
raiz = No("Raiz")
filho1 = No("Filho 1")
filho2 = No("Filho 2")
neto1 = No("Neto do Filho 1")

# Construindo a árvore
raiz.adicionar_filho(filho1)
raiz.adicionar_filho(filho2)
filho1.adicionar_filho(neto1)

# Mostrando a árvore
raiz.mostrar()
```

### 🖨️ Saída esperada:
```
- Raiz
  - Filho 1
    - Neto do Filho 1
  - Filho 2
```

---

## ✅ Vantagens:
- Organiza dados hierarquicamente.
- Permite representação de estruturas como sistemas de arquivos, árvores genealógicas, jogos, etc.

## ⚠️ Desvantagens:
- Mais complexa que listas ou dicionários.
- Pode exigir mais memória e lógica para percorrer ou modificar.