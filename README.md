# README

Este projeto contém diferentes implementações de classes que representam funcionários comissionados e funcionários comissionados com salário base. Cada pasta contém uma versão específica do código, com diferentes abordagens de implementação.

## Estrutura do Projeto

- **bonificacao/**: Implementação básica de um funcionário comissionado e uma versão que inclui um salário base.
- **baseplus/**: Implementação de um funcionário comissionado com salário base, sem uso de herança.
- **comheranca/**: Implementação de um funcionário comissionado com salário base, utilizando herança.
- **comissionemployee/**: Implementação de um funcionário comissionado com salário base, utilizando herança.
- **comissionemployee/**
   - Contém a implementação básica de um funcionário comissionado (`CommissionEmployee`).
   - A classe gerencia informações como nome, número de segurança social, vendas brutas e taxa de comissão, além de calcular os ganhos com base nas vendas.

- **heranca/**
   - Implementa um funcionário comissionado com salário base (`BasePlusCommissionEmployee`) utilizando herança da classe `CommissionEmployee`.
   - A classe estende a funcionalidade de `CommissionEmployee`, adicionando um salário base ao cálculo dos ganhos.

- **herancamodificada/**
   - Contém uma versão modificada de `BasePlusCommissionEmployee`, onde a função `print()` e `earnings()` são sobrescritas para reutilizar código da classe base (`CommissionEmployee`).

- **semheranca/**
   - Implementa um funcionário comissionado com salário base (`BasePlusCommissionEmployee`) sem utilizar herança.
   - A classe gerencia todas as propriedades diretamente, sem depender de uma classe base.

## Como Compilar e Executar

Para compilar e executar qualquer uma das implementações, siga os passos abaixo:

1. Navegue até a pasta desejada (`bonificacao/`, `baseplus/`, ou `comheranca/`).
2. Compile os arquivos `.cpp` usando um compilador C++. Por exemplo:
   ```bash
   g++ main.cpp arquivos_de_implementacao.cpp -o programa