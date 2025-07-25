Conforme solicitado, aqui foi proposto o meu modelo. Ele consiste em um ajuste do modelo original, onde:

* inicialmente, as classes foram rebalanceada limitando a quantidade de imagens da etapa de treino pela classe minoritária;
* foi acrescentada mais uma camada de convolução a entrada (totalizando 3 camadas);
* foi adicionado camadas de batch normalization entre as camadas anteriores;
* a quantidade de mini-batch foram auteradas para 30;
* a quantidade de feature também foi ampliada para 20;
* o dropout foi ajustado para 0.4;
* foi utilizado a biblioteca proposta no livro para determinar um melhor valor inicial para o learning ratio. O melhor valor encontrado para o lr foi igual a 2,96e-2 o qual foi utilizado.

O modelo conseguiu uma acurácia de aproximadamente 92%, além de um baixo de valor de falso positivo.  
