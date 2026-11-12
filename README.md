    Previsão de Vendas e Faturamento com Facebook Prophet

Este projeto utiliza modelagem de séries temporais com o Facebook Prophet para prever vendas e faturamento de um dataset fictício.
O objetivo é demonstrar habilidades em ciência de dados, incluindo:

Manipulação e limpeza de dados

Análise exploratória

Visualização gráfica

Criação e avaliação de modelos preditivos

Comunicação de resultados


    Tecnologias Utilizadas

Python 3.9+

Pandas

NumPy

Matplotlib

Seaborn

Facebook Prophet

Jupyter Notebook

    Análises Realizadas
🔹 1. Análise Exploratória

Verificação de tipos de dados

Identificação de valores nulos

Conversão de datas

Ordenação da série temporal

Visualização da tendência de vendas e faturamento

🔹 2. Modelagem com Prophet

Foram criados dois modelos:

Modelo 1 — Previsão de Vendas

Modelo 2 — Previsão de Faturamento

Ambos com:

Sazonalidade anual

Sazonalidade semanal

Modo aditivo

🔹 3. Forecast de 90 dias

O Prophet gera:

Previsões (yhat)

Intervalo inferior (yhat_lower)

Intervalo superior (yhat_upper)

Componentes de tendência e sazonalidade

🔹 4. Cálculo de Erro (MAE)

O erro médio absoluto foi calculado para avaliar a precisão dos model



    Conclusões

O Prophet capturou bem tendências de vendas e faturamento.

O modelo é simples, eficiente e de fácil interpretação.

O MAE ajuda a entender o nível de precisão da previsão.

Este projeto demonstra domínio em:

ETL com Pandas

Visualização

Machine Learning para séries temporais

Storytelling com dados


## Relatório interativo no Power BI

O arquivo [`faturamento.pbix`](projeto%20de%20analise%20de%20series%20temporais/faturamento.pbix) abre no Power BI Desktop e apresenta a evolução mensal do faturamento, faturamento por categoria, unidades vendidas por produto e filtros por período e loja.

Para visualizar, baixe o arquivo e abra-o no Power BI Desktop. O relatório usa dados fictícios de vendas deste projeto.
