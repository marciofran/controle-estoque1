Sistema de Estoque de Peças
Este projeto implementa um Sistema de Estoque de Peças simples, utilizando HTML, CSS e JavaScript. A aplicação permite o cadastro de peças, consulta do estoque e remoção de itens com base em um código de identificação. Os dados são armazenados no Local Storage do navegador, permitindo que as informações persistam entre as sessões.

Funcionalidades
1. Cadastrar Peças
O usuário pode cadastrar peças fornecendo:
Nome da peça
Fabricante
Preço
Código de barras (opcional)
O sistema atribui automaticamente um código único para cada peça cadastrada.
O cadastro de peças é salvo no Local Storage para garantir que as informações sejam mantidas mesmo após o fechamento do navegador.
2. Consultar Peças
O usuário pode visualizar todas as peças cadastradas no sistema.
A lista exibida inclui informações como:
Código da peça
Nome
Fabricante
Preço
Código de barras (se presente)
3. Remover Peças
O usuário pode remover peças do estoque informando o código da peça ou o código de barras.
A peça é removida da lista e o Local Storage é atualizado para refletir a mudança.
