# Etapas do Processo (ou Pipeline de Ciência de Dados)
![alt text](/Imagens/image2.png)

O processo de Ciência de Dados envolve várias etapas fundamentais para transformar dados brutos em informações valiosas.

## 1. Obtenção dos Dados
O primeiro passo no pipeline é **coletar os dados**. Eles podem vir de várias fontes, como:
- **Bancos de dados**
- **APIs**
- **Web scraping**
- **Arquivos CSV, XLS etc.**

## 2. Análise Exploratória
Nesta fase, o objetivo é compreender a estrutura dos dados e obter insights iniciais. Isso inclui:
- **Compreensão dos dados** por meio de observações estatísticas:
    - **Valor mínimo e máximo**
    - **Média e mediana**
    - **Desvio padrão** e **variância**
- **Criação de gráficos e visualizações** para entender melhor as distribuições das colunas/features.
- **Exploração das correlações** entre variáveis.

## 3. Pré-processamento
O pré-processamento é uma etapa essencial para **preparar os dados** para o treinamento do modelo. Nesta fase, cuidamos da:
- **Verificação de consistência e qualidade dos dados**, como:
    - **Tratamento de valores nulos**
    - **Identificação de valores inconsistentes ou inválidos**
- **Normalização ou padronização** dos dados, se necessário.
- **Feature engineering**: Geração de novos atributos que possam enriquecer a base de dados, criando **novas features/colunas**.

## 4. Escolha e Treinamento do Modelo
Após preparar os dados, é hora de escolher o **algoritmo** de machine learning adequado para o problema. Nesta fase:
- **Escolha do modelo** (regressão, classificação, clustering, etc.).
- **Treinamento** com os dados históricos para aprender padrões e realizar previsões.

## 5. Análise dos Resultados
Após o treinamento, o modelo é avaliado usando métricas como:
- **Acurácia**
- **Precisão**
- **Recall**
- **F1-score**

O objetivo é verificar a **eficácia** do modelo em relação ao problema proposto.

## Adendo:
A etapa 2 (Análise Exploratória) e a etapa 3 (Pré-processamento) muitas vezes podem se mesclar. <br>
Para criar gráficos e visualizações, assim como explorar a correlação entre as variáveis, é necessário que os dados sejam coerentes e não-nulos. <br>
Então, exige-se que o tratamento desses valores seja feito antes das visualizações.

<br>

[![➡ Próxima Seção](https://img.shields.io/badge/-➡_Próxima_Seção-blue?style=for-the-badge&color=007BFF)](https://github.com/biankyrou/data-science-lab/blob/main/Guia%20de%20Estudos/1-%20Introdu%C3%A7%C3%A3o/4-%20Compreens%C3%A3o%20do%20Dom%C3%ADnio.md)
