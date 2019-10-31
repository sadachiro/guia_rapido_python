

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

lista_especial = '~!@#$%^&*()_+|`-=\\[]{};:\',./<>?*-+"\n\t'
for c in lista_especial:
	print(str(normalize('NFKD', 'coloque aqui seu texto áàãâäéèêëíìîïóòõôöúùûüçñÀÁÃÂÉÊÍÓÕÔÚÜÇ').encode('ASCII', 'ignore').decode('ASCII')).lower().replace(c, ''))
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
eyJoaXN0b3J5IjpbODAzOTM3NDM5LC03OTMxOTI0OSwtMTMwNz
U0OTA5NF19
-->