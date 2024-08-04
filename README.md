# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

## 🚀 Passo a Passo

### 1. Selecionar Dataset

-   Naveguei até a pasta `datasets` deste repositório.
-   Escolhi o dataset: dataset-1000-com-preco-promocional-e-renovacao-estoque.
-   Fiz o upload do dataset no SageMaker Canvas.

### 2. Construir/Treinar

-   Importei o dataset selecionado.
-   Configurei as variáveis de entrada e saída de acordo com os dados. Usei a coluna FLAG_PROMOCAO.
-   Iniciei o treinamento do modelo.

### 3. Analisar

-   Após o treinamento, examinei as métricas de performance do modelo.
-   Os valores das métricas encontradas foram: Avg. wQL 1.200; MAPE 1.000; WAPE 1.000; RMSE 0.141; MASE 0.224

### 4. Prever

-   Usei o modelo treinado para fazer previsões de estoque, mas não encontrei variações nos valores. Eram sempre 0.
