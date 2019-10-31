

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



---
**** - 
```python
# --------------------------------------------------
```
---



---

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzNDk2NDE1MzgsLTc5MzE5MjQ5LC0xMz
A3NTQ5MDk0XX0=
-->