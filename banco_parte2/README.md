# Objetivo geral

Extender o desafio anterior, separando as funções existentes em funções de saque, depósito e extrato, e criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária. 

## Desafio

Tornar o código da [parte 1](../banco_parte1/banco.py) mais modularizado e adicionar funcionalidades.

### Função de depósito

A função de depósito deve receber argumentos apenas por posição (positional only).

### Função de saque

A função saque deve receber apenas argumentos por nome (keyword only).

### Função de extrato

A função de extrato deve receber os argumentos tanto por posição e nome. Argumento posicional: saldo, argumento nomeado: extrato.

### Novas funções: criar usuário e criar conta corrente

Armazenar usuários em uma lista, um usuário é composto por : nome, data de nascimento, cpf e endereço. O endereço é uma string com formato: logradouro - nro - bairro - cidade/sigla estado. Não deve ser possível cadastrar dois usuários com o mesmo CPF.
