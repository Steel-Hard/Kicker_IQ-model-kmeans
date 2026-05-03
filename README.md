#  Kicker_IQ-model-kmeans
  Este é o ambiente de pesquisa e treinamento do modelo de Machine Learning.
   * Linguagem: Python.
   * Propósito: Analisar dados de atletas e treinar um modelo de agrupamento (K-Means) para classificar perfis (ex: identificar quem é um atleta "explosivo" vs "resistente").
   * Arquivos Chave:
       * src/k-means_model.ipynb: Um Jupyter Notebook onde o modelo é desenvolvido e testado.
       * requirements.txt: Lista dependências como scikit-learn (para o ML) e skl2onnx (para exportar o modelo).
       * data/ e model/: Pastas para armazenar os datasets e os arquivos do modelo gerado.
   * Fluxo: A equipe usa este ambiente para gerar um arquivo .onnx (o modelo pronto) e um scaler_params.json (parâmetros de normalização).
