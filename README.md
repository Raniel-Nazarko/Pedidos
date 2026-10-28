# Culto Salgados — visualização pública de pedidos

Página estática responsiva para consultar pedidos armazenados na coleção `pedidos` do projeto Firebase `cardapio-7bca4`. Permite filtrar pendentes/todos/entregues/cancelados, marcar pedido como entregue, cancelar ou excluir. Não exige telefone do cliente.

## Publicação
Envie o conteúdo desta pasta para a raiz de um repositório GitHub separado e ative GitHub Pages em Settings → Pages → Deploy from a branch → `main` → `/(root)`.

## Atenção
Esta página foi feita conforme a decisão de deixar os pedidos públicos e permitir alteração/exclusão por qualquer pessoa que consiga abrir a página. As regras públicas do Firestore liberam operações em todas as coleções do banco, não somente `pedidos`. Isso permite adulteração/exclusão de dados. Não use para dados privados.
