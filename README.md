# Terraform Conditional Expressions AWS VPC

Este projeto é uma demonstração de como usar expressões condicionais no Terraform para criar uma VPC (Virtual Private Cloud) na AWS (Amazon Web Services) de forma dinâmica.

Os arquivos `main.tf`, `variables.tf` e `network.tf` contém as configurações necessárias para criar e configurar a VPC, incluindo a definição de variáveis ​​e as regras de condição.

## Requisitos

- Terraform 0.12 ou superior
- Conta na AWS

## Notas

- Este projeto é apenas uma demonstração e não deve ser usado em produção sem modificações adequadas.
- Certifique-se de que você tem permissão para criar recursos na sua conta AWS antes de executar o Terraform.

## Maiores detalhes

- O arquivo main.tf é o principal arquivo de configuração do Terraform, onde são declaradas os recursos que serão gerenciado pelo Terraform.
  -O arquivo variables.tf é onde são declaradas as variáveis usadas no projeto, onde o usuário pode configurar como desejar.
- O arquivo network.tf é onde são declaradas as regras de condição para a criação da VPC, essas regras são baseadas nas variáveis declaradas no arquivo variables.tf.
