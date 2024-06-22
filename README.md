# TDNN para previsão de preço de mercadoria

O preço de uma determinada mercadoria disposta para ser comercializada no mercado financeiro de ações possui um histórico de variação de valor conforme mostrado na tabela apresentada no Anexo.

Um pool de pesquisadores estará tentando aplicar redes neurais para tentar prever o comportamento futuro deste processo. Assim, pretende-se utilizar uma arquitetura perceptron multicamadas, com topologia “Time Delay” (TDNN), conforme mostrada na figura abaixo: 

<img src='./img/Imagem1.png' >

As topologias candidatas para serem adotadas no mapeamento do problema acima são especificadas como se segue:

Rede 1 $\rightarrow$ 05 entradas (p = 05) com N1 = 15  
Rede 2 $\rightarrow$ 10 entradas (p = 10) com N1 = 25  
Rede 3 $\rightarrow$ 15 entradas (p = 15) com N1 = 50
