# Desafio Senior - Exercício Pesquisador 2020¶
Repositorio com o desafio senior.

### base de dados: sms_senior.csv

### artigo : artigo.pdf

### notebook: senior_desafio.ipynb

### Metodos:
* inicializa_dataset(dataset_path) : 
   * Recebe como entrada dataset_path, ou seja, o diretorio no qual se encontra a base em csv. 
   * Output: Grafico em WordCloud.
  
*  visualiza_matriz_contagem(df):
   * Recebe como entrada df. Esta variavel esta definida como global, portanto a funcao necessita somente ser executada.
   * Output: Bag Of Words previamente fornecida.
 
* pre_process_words(df):
   * Recebe como entrada df, ou seja, a bag of words.
   * Output: Lista com palavras e respectivas somas de frequencia absoluta.
 
 * classificador(features, target):
   * Recebe como entrada features da base de dados e a variavel target (Classificao entre Spam ou Nao Spam). Realiza o split entre conjuntos de treino e teste e executa uma lista de algoritmos classificadores
   * Output: Metricas de avaliacao, tais como, recall, acuracia, F1 Score, Matriz de Confusao.
 
 





