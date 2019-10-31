

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
**normalize** - remover caracteres especiais
```python
str(normalize('NFKD', texto).encode('ASCII', 'ignore').decode('ASCII')).lower().replace(c, '')
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
eyJoaXN0b3J5IjpbLTc5MzE5MjQ5LC0xMzA3NTQ5MDk0XX0=
-->