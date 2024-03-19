Nome: José Fernando de  Araújo Neto
Modelo: Vendas online
Relatório Entidade e atributos.
Cliente: nome(nome e sobrenome), cpf(chave), telefone, email, endereço(endereço por ter muito detalhe coloquei como composto para termos o endereço certo e evitar erros por isso cep, complemento, rua e número).
Produto: nome, idProduto(chave),estoque,valor,descrição e garantia.
Avaliação: Estrelas,comentarios(para avaliar de forma completa o produto).
Anunciante:nome(chave).
Pedido: idPedido(chave),cupom,dataPedido(data quando foi pedido),dataEntrega(data estimada para chegada do produto) e frete.
Pagamento:idPagamento(chave),valorTotal , desconto(verifica se ouve algum cupom a ser aplicado ou se tem algum desconto no produto).
Envio: codigoRastreio(codigo para poder ver onde o produto esta e acompanhar ele).
