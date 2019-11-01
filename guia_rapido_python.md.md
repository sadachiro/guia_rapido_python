

# Guia Rápido Python
## Comandos

**print** - imprimir texto no console
```python
a, b = 'Olá', 'Mundo'
print('{} {}'.format(a, b))
Olá Mundo
# --------------------------------------------------
print('*'*50)
**************************************************
# --------------------------------------------------
```
---
**set** - remover items iguais
```python
set([1,2,3,4,4,4])
{1, 2, 3, 4}
# --------------------------------------------------
list(set([1,2,3,4,4,4]))
[1, 2, 3, 4]
```

**normalize** - remove lista de caracteres especiais e caixa baixa
```python
from unicodedata import normalize
lista_especial = '~!@#$%^&*()_+|`-=\\[]{};:\',./<>?*-+"\n\t'
for c in lista_especial:
	texto_limpo = str(normalize('NFKD', 'fazendo a limpa nos chars especiais áàãâäéèêëíìîïóòõôöúùûüçñÀÁÃÂÉÊÍÓÕÔÚÜÇ~!@#$%^&*()_+|`-=\\[]{};:\',./<>?*-+').encode('ASCII', 'ignore').decode('ASCII')).lower().replace(c, '')
print(texto_limpo)
# --------------------------------------------------
```

```python
import string
def clean(instr):
    return instr.translate(None, string.punctuation + ' ')
```

---
**** - 
```python
# --------------------------------------------------
```
---



---

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM4OTAwMDc4NCwtMTM0OTY0MTUzOCwtNz
kzMTkyNDksLTEzMDc1NDkwOTRdfQ==
-->