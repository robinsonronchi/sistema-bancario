# Sistema Bancário V3 POO (Programação Orientada à Objetos)

## Objetivo Geral

Separar as funções existentes de saque, depósito e extrato em funções. Criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária.

## Desafio

Precisamos deixar nosso código mais modularizado, para isso vamos criar funções para as operações existentes: sacar, depositar e visualizar extrato. Além disso, para a versão 2 do nosso sistema precisamos criar duas novas funções: criar usuário (cliente do banco) e criar conta corrente (vincular com usuário).

### Separar em funções

Devemos criar funções para todas as operações do sistema. Para exercitar tudo o que aprendemos neste módulo, cada função vai ter uma regra na passagem de argumentos. O retorno e a forma como serão chamadas, pode ser definida por você da forma que achar melhor.

## Operações

### Saque

A função saque deve receber os argumentos apenas por nome (keyword only). Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrato.

### Depósito

A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. Sugestão de retorno: saldo e extrato.

### Extrato

A função extrato deve receber os argumentos por posição e nome (positional only e keyword only). Argumentos posicionais: saldo, argumentos nomeados: extrato.

## Novas Operações

Novas funções Precisamos criar duas novas funções: criar usuário e criar conta corrente. Fique à vontade para adicionar mais funções, exemplo: listar contas.

### Criar Usuários

O programa deve armazenar os usuários em uma lista. Cada usuário é composto por: nome, data de nascimento, CPF e endereço. O endereço deve ser uma string com o formato: logradouro, número - bairro - cidade/estado. Apenas os números do CPF devem ser armazenados. Não é permitido cadastrar dois usuários com o mesmo CPF.

### Criar Conta corrente

O programa deve armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo: “0001”. O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.

### Dicas

Para vincular um usuário a uma conta, filtre a lista de usuários buscando o número do CPF informado para cada usuário da lista.