# js

JavaScript é considerado um “bloqueador de recursos" enquanto é analisado. Isso significa que a renderização do HTML é bloqueada enquanto o código JavaScript é analisado.

### Lugares que a tag scrip pode ser colocado

O elemento scrip pode ser declarado em qq parte do codigo, desde que seja levado em consideração que ele ganha precedência.

Existem dois atributos do elemento que tem comportamentos diferentes

![Screenshot](assets/Captura%20de%20tela%20de%202023-10-18%2014-49-57.png)

### Async

Usado para indicar ao navegador que o script pode ser executado junto com o html (assíncrono) e sua execução pode acontecer a qq momento. Sendo assim não tem acesso aos dados do html depois da execução.

Pode ser colocado na head.

### Defer

Usado para indicar o navegador que o script pode ser carregado junto com o html (assíncrono), mas executado somente quando terminar a execuçao do html. Sendo assim tem acesso a todos os dados do html.

Pode ser colocado na head.