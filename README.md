# previsao-tributária

A previsão tributária para o ano de 2025 utilizou dos dados disponibilizados no portal de transparência do Estado de Alagoas objetivando prever as receitas do estado através da arrecadação do ICMS, IRRF, IPVA e ITCD.
Utilizando das metodologias de Suavização Exponencial e de Box-Jenkins, comparou-se o resultado dos melhores modelos de ambos os métodos utilizando a média absoluta percentual dos erros.

Para o modelo de Box-Jenkins, foram encontrados os melhores modelos através da análise gráfica dos gráficos de autocorrelação e autocorrelação parcial, assim como foi realizado uma array com as combinações possíveis a partir desta. Disto, tem-se também a comparação com os resultados obtidos através do método _autoarima_, do pacote _pmdarima_, com o intuito de compatibilizar os melhores modelos.
