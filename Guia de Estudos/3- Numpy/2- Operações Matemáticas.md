# Operações Matemáticas com NumPy

## Operações Básicas com Arrays

O NumPy permite realizar várias operações matemáticas em arrays de maneira simples e eficiente.

### Exemplo de um Array Unidimensional:

```python
import numpy as np

a = np.random.randint(10, size=(5,))
print(a)  # Exemplo: array([5, 7, 2, 8, 1])
```

### Operações Matemáticas Básicas:
#### Soma, Subtração, Divisão, Multiplicação, Exponenciação e Comparação
Adicionando ou subtraindo um valor de cada elemento no array.
```python
a + 10  # Resultado: array([15, 17, 12, 18, 11])
a - 5   # Resultado: array([ 0,  2, -3,  3, -4])
a * 2  # Resultado: array([10, 14,  4, 16,  2])
a / 2  # Resultado: array([2.5, 3.5, 1. , 4. , 0.5])
a ** 2  # Resultado: array([25, 49,  4, 64,  1])
a < 5  # Resultado: array([False, False, True, False, True])
```


## Operações Básicas entre Arrays
Quando se trabalha com dois arrays de mesma forma (shape), é possível realizar operações elemento por elemento. Exemplo:
```python
a = np.array([2, 3, 9, 4])
b = np.array([7, 1, 8, 5])

a + b  # Resultado: array([ 9,  4, 17,  9])
a - b  # Resultado: array([-5,  2,  1, -1])
```

<br>

[![➡ Próxima Seção](https://img.shields.io/badge/-%E2%9E%A1_Pr%C3%B3xima_Se%C3%A7%C3%A3o:_Fun%C3%A7%C3%B5es_de_Agrega%C3%A7%C3%A3o_e_Reshape-blue?style=for-the-badge&color=007BFF)](https://github.com/biankyrou/data-science-lab/blob/main/Guia%20de%20Estudos/3-%20Numpy/3-%20Fun%C3%A7%C3%B5es%20de%20Agrega%C3%A7%C3%A3o%20e%20Reshape.md)
