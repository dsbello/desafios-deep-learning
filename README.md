# Desafio DeepLearning
## Modelo de classificação binário de imagens.

A estruturação do projeto do desafio foi realizada da seguinte maneira:

1. A descrição do processo da obtenção dos dados foi definido e detalhado no notebook "Obtecao dos dados atraves de web scrapping.ipynb".
2. O processo de escolha, comparação e seleção do modelo e arquitetura escolhido se encontra no notebook "Escolha do modelo da rede neural.ipynb".
3. A partir desses dois notebook, todo o projeto da criação de uma modelo de classificação está descrito no notebook "Projeto de modelo de classificação de imagens..ipynb".
  >Lá está descrito todas as técnicas utilizadas, as ponderações e os processos realizados para a construção, compilação e treinamento do modelo.
4. O modelo foi salvo no arquivo "saved_model.pb".
5. O bando de dados está salvo na pasta "airplane_images".
6. Recomenda-se utilizar o método "tf.keras.models.load_model()" para carregar o modelo e a partir daí realizar as previsões. Caso queira executar novamente o código, algumas adaptações podem ser necessárias caso não esteja utilizando o windows.