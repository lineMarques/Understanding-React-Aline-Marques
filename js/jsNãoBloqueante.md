# js linguagem nao bloqueante

Em um sistema bloqueante as requisições seriam enfileiradas e depois disso seriam processadas uma a uma, dessa forma não seria possível processar várias delas ao mesmo tempo. Ou seja o cliente que tem a requisição mais nova só terá sua requisição processada depois que as requisições mais velhas tiverem sido processadas por inteiro.

E nas não-bloqueantes teremos que a requisição do cliente mais novo poderá ser processada (ou pelo menos uma parte dela) antes que todas requisições que o servidor recebeu antes dela sejam processadas

