# Desafio_Api

A API exibe a rota com documentação swagger (http://.../api-docs).
A API possui 3 operações:

- Registrar venda: Recebe os dados do vendedor + itens vendidos. Registra venda com status "Aguardando pagamento";
- Buscar venda: Busca pelo Id da venda;
- Atualizar venda: Permite que seja atualizado o status da venda.

OBS.: e os possíveis status são: Pagamento aprovado | Enviado para transportadora | Entregue | Cancelada.

De: Aguardando pagamento Para: Pagamento Aprovado

De: Aguardando pagamento Para: Cancelada

De: Pagamento Aprovado Para: Enviado para Transportadora

De: Pagamento Aprovado Para: Cancelada

De: Enviado para Transportador. Para: Entregue