## 🔧 Exemplo de Uso

Criamos uma estrutura com um CEO, um gerente e vários trabalhadores. Depois imprimimos a hierarquia e removemos um subordinado.

```python
ceo = Employee("Alice", "CEO")
maneger = Employee("Bob", "Manager")

# Criando os trabalhadores
worker1 = Employee("worker1", "Worker")
...
worker10 = Employee("worker10", "Worker")

# Construindo a hierarquia
ceo.add_subordinate(maneger)
maneger.add_subordinate(worker1)
...
maneger.add_subordinate(worker10)

# Imprimindo
ceo.print_hirarchy()

# Removendo e imprimindo de novo
maneger.remove_subordinate(worker1)
print("\nApós remover um subordinado:")
ceo.print_hirarchy()
```