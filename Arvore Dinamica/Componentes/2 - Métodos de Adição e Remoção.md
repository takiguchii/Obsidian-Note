## ➕ Adicionando e Removendo Subordinados

### `add_subordinate`
Adiciona um objeto `Employee` à lista de subordinados.

```python
def add_subordinate(self, Employee):
    self.subordinates.append(Employee)
```

### `remove_subordinate`
Remove um subordinado se ele existir na lista. Se não estiver, exibe uma mensagem de erro.

```python
def remove_subordinate(self, Employee):
    if Employee in self.subordinates:
        self.subordinates.remove(Employee)
    else:
        print(f"{Employee.name} não é um subordinado {self.name}.")
```