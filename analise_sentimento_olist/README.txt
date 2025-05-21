Análise de Sentimento em Avaliações - Olist (PLN)
Este projeto aplica técnicas de Processamento de Linguagem Natural (PLN) para realizar uma análise de sentimento em comentários deixados por clientes da plataforma Olist, utilizando dados disponíveis publicamente no Kaggle.

O objetivo é classificar automaticamente os sentimentos expressos nas avaliações em positivos, neutros ou negativos, a fim de compreender a experiência dos consumidores no e-commerce e gerar insights relevantes para o negócio.

Base de Dados
Foi utilizada a base "Brazilian E-Commerce Public Dataset by Olist", disponível no Kaggle:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

As principais tabelas utilizadas foram:

olist_order_reviews_dataset.csv: avaliações dos clientes.

olist_orders_dataset.csv: informações sobre os pedidos.

Etapas do Projeto
Importação e visualização dos dados

Limpeza e pré-processamento textual

Remoção de pontuação, stopwords e acentuação

Conversão para letras minúsculas

Classificação dos sentimentos

Notas 1 e 2: Negativo

Nota 3: Neutro

Notas 4 e 5: Positivo

Tokenização e Vetorização

Transformação dos textos em vetores numéricos com TF-IDF

Modelagem

Aplicação de algoritmos como Regressão Logística e Naive Bayes

Avaliação dos Modelos

Acurácia, matriz de confusão e F1-Score

Geração de Visualizações e Insights

Nuvens de palavras

Distribuições de notas e termos mais frequentes

Resultados
O modelo demonstrou bom desempenho na classificação de sentimentos.

A maioria das avaliações positivas menciona rapidez na entrega e qualidade do produto.

Avaliações negativas estão associadas a atrasos, atendimento insatisfatório e produtos com defeito.

Tecnologias Utilizadas
Python (Jupyter Notebook)

Pandas, NumPy

Scikit-learn

NLTK

Matplotlib, Seaborn

WordCloud

Thalita Dantas 
Contato: https://www.linkedin.com/in/thalitadataanalyst/