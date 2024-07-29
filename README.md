# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Neste Lab DIO, foi criado a previsão de estoque baseadas em Machine Learning (ML).
## 📋 Passo a passo

### 1. Selecionar Dataset

-   Naveguei até a pasta `datasets` deste repositório. 
-   Escolhi o Dataset 'dataset-1000-com-preco-variavel-e-renovacao-estoque' para treinar o modelo de previsão de estoque.
-   Fiz o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   No SageMaker Canvas, importei o dataset escolhido.
-   Configurei as variáveis de entrada e saída de acordo com os dados (no caso, Quantidade_Estoque e Data).
-   Iniciei o treinamento do modelo na opção mais rápida, que durou aproximadamente 20 minutos. A opção mais demorada tinha um tempo estimado de 4 horas.
    Aqui vale um adendo, precisei de algumas horas de estudo na AWS, testando modelos, procurando entender a plataforma antes de iniciar o desafio. Com 1o horas já havia
    uma cobrança de aproximadamente 12 dólares.
    Com receio que esse valor só aumentasse, escolhi treinar e analisar o modelo de maneira rápida e usando o menor recurso possível.
    Ou seja, usei apenas um produto e uma data para realizar a análise.

### 3. Analisar

-   Após o treinamento, examinei as métricas de performance do modelo.
   ![metricas](https://github.com/user-attachments/assets/2e2e1e45-8961-4138-a9b7-0f381463907e)
-   Verifiquei as principais características que influenciam as previsões.

### 4. Prever

-   Usei o modelo treinado para fazer previsões de estoque.
-   Exportei os resultados e analisei as previsões geradas.

![single_prediction_results](https://github.com/user-attachments/assets/8f04158b-9830-4a70-89d6-cea35a592a73)


