## Compreensão do Domínio  
Antes de aplicar o pipeline de Ciência de Dados, é fundamental compreender o **domínio do problema**. A eficácia das análises e dos modelos está diretamente ligada ao entendimento do contexto e à clareza dos objetivos que queremos alcançar. 

### A importância de ter um objetivo
A Ciência de Dados deve ser orientada por objetivos bem definidos, garantindo que as análises tenham propósito. Abaixo estão alguns exemplos de objetivos comuns:  
- **Previsão:** Antecipar eventos futuros, como vendas ou demanda de produtos.  
- **Determinantes:** Identificar quais fatores influenciam um resultado, como a evasão de estudantes ou a retenção de clientes.  
- **Precificação:** Estimar o valor de mercado de imóveis com base em características como localização, área e número de quartos.

### A importância de se ter um `target`  
O `target` é comumente associado a um objetivo específico que desejamos alcançar ou prever com a aplicação de Ciência de Dados. Ele representa a **variável-alvo** que o modelo ou análise deve explicar ou prever. Definir corretamente o `target` é essencial, pois ele direciona as escolhas metodológicas e garante que as etapas do processo estejam alinhadas com a pergunta ou problema em questão.

![image](https://github.com/user-attachments/assets/f15d16ef-d1d2-4e14-8f08-3a3d984a1818)

Introduzindo o conceito de Machine Learning focado em Aprendizado Supervisionado, é a partir da escolha do **target** (y) e das **features** (nossas colunas, x), que escolhemos e treinamos o nosso algoritmo. **Learner** representa o algoritmo de aprendizado que será usado para "aprender" a relação entre as features. Após o aprendizado, o **modelo** treinado usa novos dados (**X new**) para gerar previsões (**y predicted**), aplicando os padrões que aprendeu.

#### Exemplos de `target` em diferentes contextos:
- **Saúde:** Prever a probabilidade de um paciente desenvolver uma condição médica específica.  
- **Educação:** Prever a probabilidade de evasão com base em participação nas aulas e desempenho acadêmico.  
- **Ambientalismo:** Prever o impacto de políticas de redução de emissões de carbono sobre a qualidade do ar em áreas urbanas.
- **Mercado Imobiliário:** Estimar o preço de venda de imóveis com base em localização e características.  
- **Comércio:** Identificar quais clientes têm maior probabilidade de abandonar o serviço (churn).

--------------------------------------------------------------------------

### Compreensão do Problema e Perguntas de Negócio  
Antes de começar, é essencial responder algumas perguntas:  
- **O que queremos resolver ou descobrir?**  
  Ex.: Estamos tentando prever quais alunos terão desempenho insuficiente ou queremos entender quais fatores mais afetam a evasão.  
- **Quais são as métricas de sucesso?**  
  Ex.: Se o objetivo é prever evasão, a métrica pode ser a **acurácia** do modelo de classificação ou o **recall**, se o foco for minimizar falsos negativos.  
- **Quais insights podem ser transformados em ações?**  
  Ex.: Por exemplo, se identificarmos que reprovações anteriores são um fator determinante na evasão, podemos propor a criação de programas de suporte e recuperação para alunos que enfrentaram dificuldades no passado.


Em resumo, o foco em um objetivo claro e na compreensão do domínio permite direcionar as análises e construir modelos que fazem sentido para o contexto específico. Sem essa base, corre-se o risco de criar soluções desconectadas da realidade ou sem aplicabilidade prática.

<br>

[![➡ Próxima Seção](https://img.shields.io/badge/-➡_Próxima_Seção-blue?style=for-the-badge&color=007BFF)](https://github.com/biankyrou/data-science-lab/blob/main/Guia%20de%20Estudos/1-%20Introdu%C3%A7%C3%A3o/5-%20Ambiente%20de%20Trabalho.md)
