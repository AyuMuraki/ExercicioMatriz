# ExercicioMatriz
 Hoje como de costume realizei um exercicio que faz a leitura de uma matriz quadrada de inteiros, imprime a diagonal principal e conta quantos números negativos que estão presentes na matriz.

# Explicação do Código

Estrutura do Código

A linha int n = int.Parse(Console.ReadLine()); lê um número inteiro n da entrada do usuário. Esse número define o tamanho da matriz n x n.
Declaração e Inicialização da Matriz

int[,] mat = new int[n, n]; declara uma matriz bidimensional de inteiros com n linhas e n colunas.
Leitura dos Valores da Matriz

O primeiro laço for percorre cada linha da matriz. Em cada iteração, uma linha de entrada é lida, e seus valores são divididos por espaços.
O segundo laço for percorre cada coluna da linha atual, convertendo as strings de entrada em inteiros e armazenando-os na matriz.
Impressão da Diagonal Principal

Console.WriteLine("Main Diagonal: "); exibe a mensagem "Main Diagonal:".
O laço for seguinte percorre os elementos da diagonal principal (onde o índice da linha é igual ao índice da coluna) e os imprime.
Contagem de Números Negativos

A variável count é usada para armazenar o número de elementos negativos na matriz.
Um laço aninhado percorre todos os elementos da matriz. Se um elemento é negativo (mat[i, j] < 0), count é incrementado.
Finalmente, o número total de valores negativos é impresso.

# Objetivo 

 Esse exercício tem como objetivo entender como as matrizes funcionam em C# e como podemos usá-las para resolver problemas do dia a dia na programação. Durante a atividade, trabalhamos com a leitura de dados em uma matriz quadrada, mostramos a diagonal principal e contamos os elementos que atendem a certos critérios, como números negativos.
