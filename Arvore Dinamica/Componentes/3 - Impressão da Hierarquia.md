## 🖨️ Impressão da Hierarquia

### Método: `print_hirarchy`
Imprime a hierarquia da empresa, recuando conforme o nível do funcionário na árvore.

```python
def print_hirarchy(self, level=0):
    ident = "    " * level
    print(f"{ident}↳ {self.name} - {self.title}")
    for subordinate in self.subordinates:
        subordinate.print_hirarchy(level + 1)
```

Cada nível adiciona um recuo para mostrar visualmente a estrutura em árvore.