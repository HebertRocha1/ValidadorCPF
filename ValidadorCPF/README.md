# Validador de CPF em Python

Projeto desenvolvido em Python com o objetivo de validar números de CPF utilizando o cálculo oficial dos dígitos verificadores.

---

## Descrição

Este projeto implementa a lógica matemática utilizada para validação de CPFs no Brasil.

O sistema verifica:

- Se o CPF possui 11 dígitos
- Se não é uma sequência inválida (ex: 11111111111)
- Se os dígitos verificadores são válidos
- Se o formato informado está correto

---

## Como funciona o algoritmo

O CPF possui dois dígitos verificadores no final do número.

O programa realiza:

1. Cálculo do primeiro dígito verificador  
2. Cálculo do segundo dígito verificador  
3. Comparação com os dígitos informados pelo usuário  
4. Retorno informando se o CPF é válido ou inválido  

---