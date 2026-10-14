# Projeto 02 — Testes de API com Postman

## Objetivo
Desenvolver testes de API utilizando Postman e JavaScript para validar o status HTTP e os dados retornados pela API.

## Ferramentas 
- Post-Man
- JavaScript
- JSONPlaceholder — API fictícia para treinamento.

## Endpoint testado
- **Método:** GET
- **URL:** https://jsonplaceholder.typicode.com/users/1

## Testes implementados
1. Validar se o nome retornado é `Leanne Graham`.
2. Validar se o status da resposta HTTP é `200 OK`.
3. Validar se o e-mail retornado é `Sincere@april.biz`.

## Resultado
Os três testes foram executados com sucesso no Postman.

Também foi realizado um teste negativo, alterando propositalmente o nome esperado para verificar se a asserção identificava a divergência.

## Observação
O JSONPlaceholder é uma API de treinamento. Os dados utilizados são fictícios e servem para praticar requisições e validações de API.
