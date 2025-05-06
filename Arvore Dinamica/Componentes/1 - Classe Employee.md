## 🧱 Classe Employee

Esta classe representa um **empregado** na hierarquia de uma empresa. Cada instância pode conter:

- `name`: o nome do empregado.
- `title`: o cargo do empregado.
- `subordinates`: uma lista de subordinados, que são outros objetos da mesma classe `Employee`.

```python
class Employee:
    def __init__(self, name, title):
        self.name = name
        self.title = title
        self.subordinates = []
```

Essa estrutura cria uma árvore onde cada nó (empregado) pode ter vários filhos (subordinados).