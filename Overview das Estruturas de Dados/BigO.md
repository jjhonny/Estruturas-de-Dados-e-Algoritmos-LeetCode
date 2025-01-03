# Big O Notation

## Big O notation serve para medir tanto a complexidade temporal, quanto a complexidade espacial de um input tipo um array. Basicamente vai descrever o quanto de tempo demora para executar o algoritmo proporcional ao input.

### O(1) - Constant Time
Independente do tamanho do input recebido o algoritmo vai executar na mesma quantidade de tempo.

**Exemplo:** Achar o primeiro elemento de um array nessa notação a velocidade seria a mesma se o array tiver 2 ou 1000 elementos, o tempo de execução é sempre o mesmo.

### O(log n) - Logarithmic Time
Conforme o tamanho do input aumente em N o tempo de execução aumenta em log N. O input cresce muito mais rápido que o tempo de execução.

### O(n) - Linear Time
O tempo de execução do algoritmo cresce linearmente com o tamanho do input. Se o input dobra de tamanho, o tempo de execução também dobra.

**Exemplo:** Percorrer todos os elementos de um array para encontrar um valor específico.

### O(n log n) - Linearicthmic time
O tempo de execução do algoritmo cresce de forma linear com o tamanho do input, mas com um fator adicional de log n, que é o tempo de execução de uma operação de busca em um array ordenado. Isso significa que o tempo de execução do algoritmo aumenta de forma linear com o tamanho do input, mas com um fator adicional de log n. 

**Exemplo:** O tempo de execução de um algoritmo de ordenação por mergesort cresce de forma linear com o tamanho do input, mas com um fator adicional de log n, pois a busca em um array ordenado demora log n.

### O(n^2) - Quadratic Time
O tempo de execução do algoritmo cresce proporcionalmente ao quadrado do tamanho do input. Se o input dobra de tamanho, o tempo de execução quadruplica.

**Exemplo:** Algoritmos de ordenação simples como o Bubble Sort, onde para cada elemento do array, percorremos todos os outros elementos.

### O(2^n) - Exponential Time
O tempo de execução do algoritmo dobra a cada novo elemento adicionado ao input. Este tipo de complexidade é geralmente encontrado em problemas de combinação e permutação.

**Exemplo:** Resolver o problema da Torre de Hanói para n discos.

### O(n!) - Factorial Time
O tempo de execução do algoritmo cresce de forma fatorial com o tamanho do input. Este tipo de complexidade é extremamente ineficiente e geralmente impraticável para inputs grandes.

**Exemplo:** Algoritmos que geram todas as permutações possíveis de um conjunto.