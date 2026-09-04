
# 🧠 Projeto: Previsão de Transtorno do Espectro Autista (TEA) usando Dados do Teste AQ-10

## 📝 Visão Geral
Este projeto visa prever o Transtorno do Espectro Autista (TEA) com base nas respostas ao teste [AQ-10 Adult (Autism Spectrum Quotient 10)](https://bibliotecadeinstrumentos.com.br/instrumentos/autism-spectrum-quotient-adult-aq-10__2d1938f9-565e-44b8-8dd9-52d34ece6bf4/pdf). O processo envolve o carregamento de dados, pré-processamento, construção e treinamento de um modelo de rede neural usando TensorFlow/Keras e avaliação de seu desempenho.

## 📊 Dataset (Conjunto de Dados)
O dataset escolhido está disponível em: [dataset evaluations](https://www.kaggle.com/datasets/stealthtechnologies/predict-autism-spectrum-disorder-asd/data) , sendo escolhido da plataforma do [kaggle](https://www.kaggle.com/).
O conjunto de dados utilizado é proveniente do Kagglehub (`stealthtechnologies/predict-autism-spectrum-disorder-asd`) e contém as respostas ao questionário AQ-10, juntamente com informações demográficas e o diagnóstico final de TEA.

### ❓ Perguntas do Teste AQ-10
O conjunto de dados inclui pontuações de A1_Score a A10_Score, correspondendo às seguintes perguntas:
- `A1_Score`: Percebe pequenos sons que os outros não notam?
- `A2_Score`: Tende a focar nos pequenos detalhes em vez do todo?
- `A3_Score`: Tem facilidade em fazer mais de uma coisa ao mesmo tempo?
- `A4_Score`: Percebe facilmente quando alguém está ficando entediado conversando com você?
- `A5_Score`: Tem facilidade em "ler nas entrelinhas" o que as pessoas dizem?
- `A6_Score`: Tem facilidade em descobrir as intenções das outras pessoas?
- `A7_Score`: Entende facilmente as intenções dos personagens em filmes ou livros?
- `A8_Score`: Gosta de colecionar informações sobre categorias (carros, plantas, etc.)?
- `A9_Score`: Sabe o que alguém está sentindo apenas olhando para o rosto da pessoa?
- `A10_Score`: Tem dificuldade em descobrir as intenções das pessoas?

## 📚 Bibliotecas Utilizadas
- `pandas`: Para manipulação e análise de dados.
- `numpy`: Para operações numéricas.
- `matplotlib.pyplot`: Para plotagem de gráficos.
- `seaborn`: Para visualizações de dados aprimoradas.
- `tensorflow`: Para construir e treinar o modelo de rede neural.
- `sklearn`: Para utilitários de aprendizado de máquina, como divisão de dados, pré-processamento e métricas de avaliação.
- `kagglehub`: Para download do conjunto de dados.
