# Desafio proposto no curso Formação Java Developer da DIO
<br>
<h2>Foi realizado da seguinte forma:</h2>
Na classe Contador, utilizamos a classe Scanner para ler os valores dos parâmetros a partir do terminal e armazená-los nas variáveis parametroUm e parametroDois, respectivamente.
Em seguida, chamamos o método contar(parametroUm, parametroDois) e capturamos a exceção ParametrosInvalidosException caso ela seja lançada.
No método contar(parametroUm, parametroDois), verificamos se o valor de parametroUm é maior ou igual ao valor de parametroDois. Caso seja, lançamos a exceção ParametrosInvalidosException com a mensagem "O segundo parâmetro deve ser maior que o primeiro".
Caso contrário, calculamos a variável contagem como a diferença entre parametroDois e parametroUm e utilizamos um laço for para imprimir os números incrementados na tela.
