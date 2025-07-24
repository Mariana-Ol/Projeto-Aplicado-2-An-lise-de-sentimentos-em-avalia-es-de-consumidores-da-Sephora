# Análise de sentimentos em avaliações de produtos de skincare da Sephora

Este projeto tem como objetivo principal desenvolver um modelo de Machine Learning capaz de classificar avaliações de consumidores de produtos de skincare da Sephora como positivas ou negativas, utilizando técnicas de Processamento de Linguagem Natural (PLN). O dataset utilizado contém avaliações de produtos de skincare da Sephora, incluindo metadados como author_id, rating, is_recommended (variável alvo: 1 para recomendado, 0 para não recomendado), review_text (variável explicativa), product_name, brand_name, entre outros.

### Metadados do Dataset
author_id: Identificador do autor da avaliação.

rating: Nota dada ao produto (escala de 1 a 5).

is_recommended: Indica se o autor recomenda o produto (1 - verdadeiro, 0 - falso).

helpfulness: Proporção de avaliações úteis (total_pos_feedback_count / total_feedback_count).

total_feedback_count: Número total de feedbacks para a resenha.

total_neg_feedback_count: Número de feedbacks negativos para a resenha.

total_pos_feedback_count: Número de feedbacks positivos para a resenha.

submission_time: Data de publicação da avaliação.

review_text: Texto principal da resenha.

review_title: Título da resenha.

skin_tone: Tom de pele do autor.

eye_color: Cor dos olhos do autor.

skin_type: Tipo de pele do autor (ex: mista, oleosa).

hair_color: Cor do cabelo do autor.

product_id: Identificador único do produto.

product_name: Nome do produto.

brand_name: Nome da marca.

price_usd: Preço em dólares.

### Ferramentas e conceitos aplicados
#### Para a construção deste projeto, diversas ferramentas e conceitos de Ciência de Dados e PLN foram empregados:

* Linguagem de Programação: Python.

* Bibliotecas Python: Pandas, NLTK, SpaCy, Scikit-learn, Matplotlib, Seaborb, Imlearn.


* Processamento de Linguagem Natural (PLN): pré-processamento de texto, remoção de stopwords, lematização e vetorização do texto.


* Machine Learning (ML): tratamento de desbalanceamento de classes da variável target, divisão da base em conjuntos de treino e teste, desenvolvimento de algoritmos de modelos de classificação (regressão logística, KNN, random forest e árvore de decisão).


### Principais resultados
O modelo de regressão logística obteve o melhor desempenho entre os testados, com uma acurácia de aproximadamente 85.88%. 