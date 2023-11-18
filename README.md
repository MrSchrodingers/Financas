# Projeto - Finanças

Projeto para aprendizado e utilização de Machine Learning, Redes Neurais e Tratamento de Dados.
A Partir dos dados fornecidos pelo Sistema de Gerenciamento de Séries do Banco Central (SGS-BC), são feitas as requisições de dados macroeconômicos do País. Assim, é feito o tratemento e análise dos dados como:

- Autocorrelação e Autocorrelação Parcial, via ACF e PACF;
- Correlação entre os dados de frequência de observação iguais;
- Análise de Estacionariedade, via os Testes de Dickey-Fuller aumentado (ADF), Kwiatkowski–Phillips–Schmidt–Shin (KPSS), Phillips-Perron (PP) e Zivot-Andrews;
- Decomposições sazonais e de tendência via decomposição clássica e STL.

Por fim é realizado ajustes para previsão dos dados macroeconômicos de interesse, utilizando modelos estatísitcos, de Machine Learning e de Redes Neurais, sendo eles:
- Estatísticos: Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors (SARIMAX) e Suavização Exponencial de Holt-Winters;
- Machine Learning: Support Vector Machine (SVM);
- Redes Neurais: Rede neural recorrente (RNN) - Gated Recurrent Unit (GRU)
Onde foram utilizadas as bibliotecas Sklearn, Statsmodels, TensorFlow, Keras e SciKeras (Integração Scikit-Learn e TensorFlow).

Pretende-se, agora, continnuar as análises com a mesma metodologia para os índices microeconômicos, índices fundamentalistas e cotações.
