# O que é Numpy?
O NumPy (Numerical Python) é uma biblioteca Python projetada para trabalhar com arrays multidimensionais e matrizes contendo números (valores numéricos). Essas estruturas de dados permitem representar eficientemente conjuntos de dados retangulares. O NumPy possui várias vantagens, incluindo: Velocidade aprimorada em operações matemáticas e manipulação de matrizes, Menor uso de memória para armazenar dados, Integração com outras bibliotecas populares como o Pandas e Scikit-Learn. Em resumo, o NumPy facilita muito o trabalho com grandes conjuntos de dados numéricos. Em vez de usar listas Python normais, podemos usar arrays NumPy que são mais rápidos e compactos.

- O NumPy é uma biblioteca Python para arrays multidimensionais e matrizes numéricas
- Vantagens do NumPy incluem velocidade aprimorada em operações matemáticas, menor uso de memória e integração com outras bibliotecas populares
- Facilita o trabalho com grandes conjuntos de dados numéricos


## Conceito de Array
![alt text](image.png)

Os arrays são estruturas de dados fundamentais na biblioteca NumPy, e podem ser classificados em diferentes dimensões:

- **1D Array**: Unidimensional (lista)
- **2D Array**: Bidimensional (matriz retangular)
- **3D Array**: Tridimensional (estrutura cúbica)

### Dimensões

As dimensões podem ser entendidas como:
- **Altura**
- **Largura**
- **Profundidade**

## Exemplo de Criação de um Array

```python
import numpy as np

a = np.array([1, 25, 4, 33, 9])
a.ndim  # saída: 1
a.shape  # saída: (5,)
``` 

# ----------------------------------------------------------------------------------------

# Imagens

## Imagem em Tons de Cinza

![alt text](image-1.png)

Cada pixel da imagem é representado por um único valor de intensidade luminosa, geralmente variando de 0 (preto) a 255 (branco). 
No caso da imagem acima, seu formato é (7, 7), indicando que é um **array 2D**.

## Imagem RGB

A imagem RGB (Red, Green, Blue) é um tipo de imagem digital onde cada pixel é representado por três valores de intensidade luminosa, um para cada componente de cor: vermelho, verde e azul.
Cada pixel da imagem é uma combinação desses três canais. Esses valores variam de 0 a 255 e representam a quantidade de cada componente de cor presente em um pixel específico.
No caso da imagem acima, seu formato é (6, 6, 3), indicando que é um **array 3D**.
