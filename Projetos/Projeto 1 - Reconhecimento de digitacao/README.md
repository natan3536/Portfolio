# Projeto Reconhecimento de digitação

Este projeto foi obtido a partir do site Kaggle, onde pode ser acessado em (“https://www.kaggle.com/competitions/digit-recognizer/overview”). O objetivo desse projeto é criar um modelo para o reconhecimento dos dígitos de 0 a 9. Os dados contidos nesse projeto são matrizes de imagens 28x28. Para obter o modelo, foi utilizada a biblioteca TensorFlow. Esta biblioteca é muito importante pois apresenta diversos recursos e permite criar técnicas e diversos modelos, como modelos convolucionais. Estes tipos de modelos são interessantes pois detectam padrões na imagem e assim trazem um ótimo ganho para o modelo.

Na imagem abaixo vemos as imagens contidas no conjunto com seus respectivos algarismos representados no conjunto. Note que para nós é simples identificar cada número, porém vemos que há várias formas de escrita, como por exemplo o “zero”, onde na imagem temos 5 zeros escritos de forma bem diferente. Isto pode ser um pouco difícil para o modelo conseguir apresentar bons resultados, mas com as camadas de convolução o modelo irá filtrar informações importantes para conseguir detectar de forma assertiva os algarismos. 

<img src="https://github.com/natan3536/Portifolio/blob/main/Projetos/Projeto%201%20-%20Reconhecimento%20de%20digitacao/imgconjuntotreino.png"/>

Durante o treinamento do modelo foi apresentado acurácia de 0.9996 assim mostrando um modelo bem treinado e com as previsões feitas com o conjunto de teste foi obtida a acurácia de 0.99117 no site Kaggle. Então o modelo apresentado é um ótimo modelo; a seguir vemos as imagens do conjunto de teste e suas respectivas previsões. Note que o modelo conseguiu prever todas as imagens que vemos abaixo e que ele conseguiu acertar mesmo com essas diferentes formas de escrita.

<img src="https://github.com/natan3536/Portifolio/blob/main/Projetos/Projeto%201%20-%20Reconhecimento%20de%20digitacao/prevconjuntoteste.png"/>

Muito obrigado a quem leu sobre este modelo. Para trabalhos futuros, vamos construir um Arduino para usar esse modelo e, de forma simultânea, vamos escrever e ver o Arduino apresentar o dígito. Quem quiser ajudar com esta questão pode entrar em contato.

Em breve serão feitas algumas alterações.
