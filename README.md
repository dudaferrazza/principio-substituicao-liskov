# Refatoração de Cálculo de Frete: Aplicação do Princípio da Substituição de Liskov (LSP)

Este projeto demonstra a refatoração de um sistema simples de cálculo de frete que inicialmente violava o Princípio da Substituição de Liskov. A solução proposta utiliza o Padrão Strategy para isolar as lógicas de cálculo de frete, garantindo que o código cliente (ProcessadorDePagamento) não seja afetado pela substituição de diferentes tipos de frete.
