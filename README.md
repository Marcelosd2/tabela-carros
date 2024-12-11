# API de Carros - WebAPI

Está é uma API RESTful desenvolvida para o gerenciamento de informações de carros, utilizando **Node.js** e **Express**.
A API permite criar, ler, atualizar excluir carros, com validação dos dados utilizando a biblioteca **Joi**.

Este é um projeto inicial de CRUD (Create, Read, Updadte, Delete,), que será expandido no futuro. Este é apenas o escopo inicial.

## Funcionalidades 

**Get /**: Retorna a ista completa de carros.
**Get /:sigla**: Retorna as informações de um carro especifico, identificado pela sigla.
**Post /**: Adiciona um novo carro à lista.
**Put /:sigla**: Atualiza  as informações de um carro especifico, identificado pela sigla.
**Delete /:sigla**: Remove um carro especifico pela sigla.
  
## Endpoints

### 1. **Get /**

Retorna a lista completa de carros disponiveis.

#### Exemplo de Resposta:

```json

[
    {
      "nome": "Ferrari",
      "sigla" "Fer",
      "velocidadeMaxima": 340,
      "potencia": 800,
      "consumo": 2.9,
      "preco":30000,
    },
]
```