# Sobre o Projeto

Projeto desenvolvido como parte do Bootcamp Heineken - Inteligência Artificial Aplicada a Dados com Copilot. Este modelo conceitual representa um sistema de e-commerce para vendas online.

📋 Estrutura das Principais Tabelas

🧑‍🤝‍🧑 Cliente
Armazena dados dos clientes (Pessoa Física e Jurídica)

Campos: ID, nome, identificação (CPF/CNPJ), endereço

📦 Pedido
idPedido (chave primária)

Cliente_id (liga com cliente)

Status (andamento do pedido)

Frete (valor do frete)

🚚 Entrega
Monitora o status das entregas

Gera código de rastreio único

Cada pedido tem uma entrega específica

🏷️ Produto
idProduto (chave primária)

Nome (nome do produto)

Preço (valor)

Categoria (tipo do produto)

💳 Tabela Pagamento
idPagamento (chave primária)

Pedido_id (qual pedido)

FormaPagamento (cartão, pix, etc.)

Status (pago, pendente)



