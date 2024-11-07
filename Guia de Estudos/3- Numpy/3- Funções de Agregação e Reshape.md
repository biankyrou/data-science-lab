## Funções de Agregação

```python
np.sum(a) / a.sum( ) - soma
np.mean(a) / a.mean( ) - média
``` 

→ Dá para somar, multiplicar etc, por eixo:

Ex: 
```python
np.sum(a, axis = 1)
```

- Tem várias outras. Ver documentação: https://numpy.org/doc/stable/reference/routines.html

## Reshape
→ Função permite alterar o shape dos arrays. Ela transforma em sequência. Ex:
```python
a = np.arange(12)
print(a) #[ 0  1  2  3  4  5  6  7  8  9 10 11]
```

- Transformando em 2D
```python
b = a.reshape(3, 4)
print(b)
#[[ 0  1  2  3]
#[ 4  5  6  7]
#[ 8  9 10 11]]
```

- Transformando em 3D
```python
c = a.reshape(2, 3, 2)
print(c)

#[[[ 0  1]
#[ 2  3]
#[ 4  5]]

#[[ 6  7]
#[ 8  9]
#[10 11]]]
´´´

→ Os shapes sempre são múltiplos. Por exemplo, ali criamos um array com arange de 12 elementos. Então, criamos um array 2D a partir dele, com 12 elementos também (3 vezes 4). Enfim, depois criamos um array 3D (2 vezes 3 vezes 2).

<br>

[![➡ Próxima Seção](https://img.shields.io/badge/-%E2%9E%A1_Pr%C3%B3xima_Se%C3%A7%C3%A3o:_Indexa%C3%A7%C3%A3o-blue?style=for-the-badge&color=007BFF)](https://github.com/biankyrou/data-science-lab/blob/main/Guia%20de%20Estudos/3-%20Numpy/4-%20Indexa%C3%A7%C3%A3o.md)
