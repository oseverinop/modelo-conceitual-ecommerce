# Desafio DIO: Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE

## Descrição do Projeto
Este desafio tem como base a modelagem de um cenário reduzido de e-commerce, desenvolvida em colaboração com a instrutora Juliana Mascarenhas. O objetivo é **refinar o modelo conceitual** apresentado e **acrescentar novos elementos ao cenário**.

## Instrutora
- [Juliana Mascarenhas](#)

## Objetivo
Refinar o modelo proposto com os seguintes ajustes:
- **Cliente PJ e PF:** Uma conta pode ser Pessoa Jurídica (PJ) ou Pessoa Física (PF), mas não pode ter ambas informações;
- **Pagamento:** Permitir o cadastro de mais de uma forma de pagamento;
- **Entrega:** Incluir status e código de rastreio.

## Ferramentas Utilizadas
- MySQL Workbench

## Resposta do Desafio
O modelo refinado pode ser visualizado abaixo:
![Modelo Conceitual Refinado](https://github.com/oseverinop/modelo-conceitual-ecommerce/blob/main/Modelo%20Conceitual%20Refinado.png)

## Comentários sobre o Modelo
- **Cliente:** Foram criadas duas entidades distintas para representar os tipos de cliente com seus dados específicos: Pessoa Jurídica e Pessoa Física.
- **Pagamento:** Três entidades foram adicionadas para representar diferentes formas de pagamento com dados específicos: PIX, Cartão e Boleto.
- **Entrega:** A entidade Entrega foi estruturada para armazenar informações de envio detalhadas como:
  - Data do pedido;
  - Data de envio;
  - Data de entrega.

---

> Este projeto foi desenvolvido como parte do bootcamp da DIO - Heineken - Inteligência Artificial Aplicada a Dados com Copilot, e é um excelente exemplo de aplicação prática de conceitos de modelagem de banco de dados.
