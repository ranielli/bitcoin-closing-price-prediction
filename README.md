# bitcoin-closing-price-prediction

Predição do preço de fechamento do Bitcoin a partir de dados de outras criptomoedas.

Os conjuntos de dados utiizados neste trabalho foram obtidos no site Investing.com

Foi utilizada a estratégia de validação cruzada K-Fold para treinamento dos dados.

Foram avaliados três modelos de regressão, disponíveis na biblioteca Scikit-Learn, com os seguintes resultados para a métrica de avaliação R2 Score:
1) LinearRegressor -> 92%
2) SVR -> 93%
3) MLPRegressor -> 94%

---

Prediction of Bitcoin closing price from other cryptocurrencies data.

The datasets used in this work were obtained from the Investing.com website.

The K-Fold cross-validation strategy was used for data training.

Three regression models, available in the Scikit-Learn library, were evaluated, with the following results for the R2 Score evaluation metric:
1) LinearRegressor -> 92%
2) SVR -> 93%
3) MLPRegressor -> 94%

---

Projeto desenvolvido para  o primeiro módulo do curso de Especialização em Inteligência Artifical Aplicada, semestre 2021/1, do Instituto Federal de Goiás - Câmpus Goiânia.
