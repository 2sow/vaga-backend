# Vaga de Back-End na 2SOW

## **O desafio**

Desenvolver uma API em PHP “puro” (Permitido microframeworks como Slim, Lumen e etc..) e Banco de Dados (relacional).
  
---

## História de usuário

Eu como gerente do restaurante de Santa Bárbara d’Oeste gostaria de cadastrar todos os clientes que fazem pedidos para entrega.

---

## Requisitos

- Gravar cliente (CPF/CNPJ deve ser único);
- Quando for pessoa física deve preencher CPF e quando for jurídica CNPJ;
- Consultar cliente;
- Editar cliente;
- Deletar cliente;

---

## Exemplo de cenário de validação

```
DADO QUE o cliente com CPF “123456789” já está cadastrado
QUANDO eu tentar cadastrar o cliente com CPF “123456789”
ENTÃO deve exibir uma mensagem que o cliente já está cadastrado
E não deve ser executado o cadastro
```

---

## Dados do Cliente

- ID
- Nome
- Tipo Pessoa (Física ou Jurídica)
- CPF/CNPJ
- Contatos
    - Telefone
    - Email
    - Celular

Obs: O Cliente pode ter 0..N Contatos

---

## Observações

- Adicionar instruções para instalação e configuração da aplicação;

## O que será avaliado?

- Qualidade de código;
- Utilização das características mais recentes das ferramentas;
- Forma com que a solução foi criada;

## Envio

Aplicação pode ser enviado via link do Bitbucket.
