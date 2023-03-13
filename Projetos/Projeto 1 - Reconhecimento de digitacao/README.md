# Projeto Reconhecimento de digitação

Este projeto foi obtido a parti do site kaggle onde pode ser acessado em ("https://www.kaggle.com/competitions/digit-recognizer/overview").
O objetivo desse projeto é criar um modelo para o reconhecimento dos dígitos 0 ate 9. Os dados contidos nesse projeto são matrixes de imagens 28x28, para obter o modelo foi utilizado a biblioteca TensorFlow. Esta biblioteca é muito importante pois apresenta diversos recursos e permite criar técnica e diversos modelos, como modelos convolucionais. Estes tipos de modelos são interessantes pois detecta padrões na imagem e assim trás um ótimo ganho para o modelo.

Na imagem abaixo vemos as imagens contidas no conjunto com seus respectivos algarismos representado no conjunto. Note que para nos é simples identificar cada numero, porem vemos que ha varias formas de escrita, como por exemplo o "zero" onde na imagem temos 5 zeros escritos de forma bem diferente. Isto pode ser um pouco difícil para o modelo conseguir apresentar bons resultados, mas com as camadas de convolução o modelo irar filtrar informações importantes para conseguir detectar de forma assertiva os algarismo. 


<img src="https://github.com/natan3536/Portifolio/blob/main/Projeto%201%20-%20Reconhecimento%20de%20digitacao/output.png"/>

Durante o treinamento do modelo obtido apresentou acurácia de 0.9996 assim mostrando um modelo bem treinado e com as previsões feita com o conjunto de teste foi obtido a acurácia de 0.99117 no site Kaggle. Então o modelo apresentado é um ótimo modelo, a seguir vemos as imagens do conjunto de teste e suas respectivas previsões. Note que o modelo conseguiu prever todas as imagens que vemos abaixo e que ele conseguir acertar mesmo com essas diferentes forma de escrita.

<img src="https://github.com/natan3536/Portifolio/blob/main/Projeto%201%20-%20Reconhecimento%20de%20digitacao/previsaoteste.png"/>

Muito obrigado para quem leu sobre este modelo.
Para trabalhos futuros vamos construir um arduino para usar esse modelo e de forma simultânea vamos escrever e ver o arduino apresentar o digito.
Quem quiser ajudar com esta questão pode entrar em contato.

Em breve sera feito algumas alterações.
