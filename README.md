# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)


### 1. Selecionar Dataset

-   lab-aws-sagemaker-canvas-estoque

### 2. Construir/Treinar

-   Coluna-alvo: PREÇO
-   Tipo de modelo: previsão de séries temporais
-   Objetivo: como o estoque vai ser afetado de acordo com a variação de preços

### 3. Analisar

-   Perda quantil ponderada média: 0.065
-   Erro percentual absoluto médio: 0.111
-   Erro percentual absoluto ponderado: 0.108
-   Raiz quadrada média de erro: 1.678
-   Erro médio absoluto escalonado: 0.847
-   Impacto na coluna QUANTIDADE_ESTOQUE: 44.15%

### 4. Prever

-   Em média, todos os produtos têm uma queda significativa no estoque, sendo que em alguns casos, o estoque chega à metade do original
-   Portanto, quanto mais o preço se reduz ao longo do tempo, mais itens do produto em questão é comprado
-   Não foram levadas em consideração datas festivas, ou produtos "da moda"
