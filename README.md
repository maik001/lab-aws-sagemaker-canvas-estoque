# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

# Resumo
Utilizando o dataset de estoque de produtos com preço promocional e renovação, obtive um impacto de colunas sendo: PRECO - 9.14%, Feriados - 2.79%, e Promoções não tendo impacto no estoque. 
Índices de Acurácia do Modelo:
- Average Weighted Quantile Loss (wQL): 0.60
- Mean Absolute Percent Error (MAPE): 0.149
- Weighted Absolute Percent Error (WAPE): 0.103
- Root Mean Square Error (RMSE): 5.977
- Mean Absolute Scaled Error (MASE): 0.310

Um detalhe importante é que eu recebi um aviso no build dizendo que faltavam valores em preço que poderiam afetar a predição, creio que isso seja um ponto a ser visto no Dataset, e tenha causado essa baixa acurária na predição do modelo, denotado pelos altos índices de RMSE e MASE.

# Resultados
![Captura de tela 2024-08-05 230609](https://github.com/user-attachments/assets/838d3762-5715-4cb1-a559-876c48516804)

# Aviso
![Captura de tela 2024-08-05 230655](https://github.com/user-attachments/assets/0324c508-d768-4f32-89ab-67c486b92e2e)
