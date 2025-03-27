# Desafio DIO: Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE

#Descrição do Desafio de Projeto
"A partir da modelagem de um cenário reduzido de e-commerce junto com a instrutora Juliana Mascarenhas foi proposto um desafio de refinar o modelo conceitual e acrescentar mais elementos ao cenário"

#Instrutora: 
Juliana Mascarenhas

#Objetivo:
Refinar o modelo apresentado no desafio acrescentando os seguintes pontos:
- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;

#Ferramentas utilizadas
MySQL Workbench

#Respostas do Desafio


#Comentários sobre a resposta:
Vinculadas a entidade Cliente foram criadas duas entidades para representar os tipos de cliente com seus dados específicos: Pessoa Juridica e Pessoa Fisica.
Vinculadas a entida Pagamento foram criadas três entidades para representar as formas de pagamento com seus dados específicos: PIX, Cartão e Boleto.
A entidade Entrega foi criada para armazenar as informações de envio de cada pedido detalhar como data do pedido, data de envio e data de entrega.
