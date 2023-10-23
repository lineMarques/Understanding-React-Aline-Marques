# Métodos de array

delete.array[1] = deleta conteudo do array, deixa a posição vaga deixando o conteudo undefined ("deixa um buraco").

array.concat = concatena dois arrays. o sinal de + é bom para concatenar strings.

array.splice(2,0, "item1", "item2") = nesse caso nao apaga, apenas acrescenta a partir da segunda posição

array.splice(2,1,"item1", "item2") = nesse caso apaga uma posição a partir da segunda posição e acrescenta.

splice() pode ser usado tanto para apagar quanto para acrescentar! Tomar cuidado com os parêmetros.

O método filter() é um recurso que permite fazer a filtragem de elementos

O método map() funciona como uma estrutura de repetição, pois percorre todos os elementos do array, executa determinada ação e retorna um novo conteúdo.