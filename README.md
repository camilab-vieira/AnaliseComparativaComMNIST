# AnaliseComparativaComMNIST
Projeto utilizado na cadeira de Introdução à Aprendizagem Profunda.

Treine e avalie 4 modelos de classificação para a base de dados de "handwritten digits" do MNIST https://en.wikipedia.org/wiki/MNIST_database.

-Um modelo base que não seja uma rede neural, como decision tree, xgboost, random forest, etc. Recomendação: use o sklearn (https://scikit-learn.org/).

-Uma MLP

-Uma rede convolucional criada por ti. Recomendação: https://pytorch.org/

Use um modelo pre treinado já consolidado na literatura para fazer transfer learning. Recomendações: https://pytorch.org/hub/pytorch_vision_vgg/

Compare os resultados dos modelos:

plote gráficos que mostrem as acurácias de cada modelo
indique para cada modelo qual foi o digito mais dificil de classificar (indique qual métrica usou para concluir isso)
argumente qual o melhor modelo levando em consideração o tempo de execução e acurácia.
Recomendação use: https://pytorch.org/vision/main/generated/torchvision.datasets.MNIST.html .
