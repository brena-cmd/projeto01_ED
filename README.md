# projeto01_ED
<h1 align="center">Matrizes esparsas</h1>
<hr>

<h3>Code by:</h3>
Brena Rodrigues (@brena-cmd)<br>
Hugo Patrício (@HugoPDF5)

<hr>

<h3>Descrição</h3>
Implementar uma matriz esparsa usando listas circulares duplamente encadeadas

<hr>

<h3>Funções</h3>
-[]List(): Construtor da classe. Deve iniciar todos os atributos da classe com valores validos.<br>
-[]∼List(): Destrutor da classe. Libera mem´oria previamente alocada.<br>
-[]void push back(int key): Insere um inteiro key ao final da lista.<br>
-[]int pop back(): Remove elemento do final da lista e retorna seu valor.<br>
-[]void insertAfter(int key, int k): Insere um novo n´o com valor key ap´os o k-´esimo n´o da lista.<br>
-[]void remove(int key): Remove da lista a primeira ocorrˆencia do inteiro key<br>
-[]void removeAll(int key): Remove da lista todas as ocorrˆencias do inteiro key.<br>
-[]void print(): Imprime os elementos da lista.<br>
-[]void printReverse(): Imprime os elementos da lista em ordem reversa.<br>
-[]bool empty(): Retorna true se a lista estiver vazia e false caso contr´ario.<br>
-[]int size(): Retorna o n´umero de n´os da lista.<br>
-[]void clear(): Remove todos os elementos da lista e deixa apenas o n´o cabeca.<br>
-[]void concat(List *lst): Concatena a lista atual com a lista lst passada por parˆametro. Ap´os essa opera¸c˜ao ser executada, lst ser´a uma lista vazia, ou seja, o ´unico n´o de lst ser´a o n´o cabe¸ca.<br>
-[]List *copy(): Retorna um ponteiro para uma c´opia desta lista.<br>
-[]void copyArray(int n, int arr[]): Copia os elementos do array arr para a lista. O array arr tem n elementos. Todos os elementos anteriores da lista s˜ao mantidos e os elementos do array arr devem ser adicionados ap´os os elementos originais.<br>
-[]bool equal(List *lst): Determina se a lista passada por parˆametro ´e igual a lista em quest˜ao. Duas listas s˜ao iguais se elas possuem o mesmo tamanho e o valor do k-´esimo elemento da primeira lista ´e igual ao k-´esimo elemento da segunda lista.

<hr>
<h3>Linguagem utilizada</h3>
C++
