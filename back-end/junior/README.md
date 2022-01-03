# Teste para Analista de Software Back-End

A proposta deste teste é criar uma sistema de cadastro de autos utilizando api-rest. 

## Como fazer seu teste
   Para realizar seu teste faça um Fork do repositório e trabalhe no branch com seu nome-sobrenome. Quando terminar faça um PullRequest deste branch e informe o link para o analista de RH que esta atuando em seu processo de seleção. 
 
## Prazo para entrega
  Você terá 44 horas (não ultrapasando 1 semana corrida).

## Api Cadastro veicular

Criar uma aplicação back-end utilizando rest-api, que utilize todos os métodos (GET, POST, PUT, PATCH, DELETE) de acordo com os requisitos abaixo:

- Permitir o cadastro de veículos
- Permitir a atualização de dados de um veiculo
- Permitir a exclusão de um veículo
- Listar com paginação os veiculos
- No cadastro deverá haver consistência das marcas forcecias (o sistema só trabalha com Ford, Volkswagen, Chevrolet)

### Especificação do projeto:
 - Fazer setup de uma API utilizando:
  - pilha de tecnologia informada pelo analista de RH responsavél pela vaga

- Implemente sua API seguindo as melhores práticas de arquitetura e design patterns.
- Utilize as libs que ache necessário na implementação da sua API.

Monte uma base de veículo com a sequinte estrutura:
```
veiculo: string,
marca: string,
ano: string,
descricao: text,
vendido: bool,
created: datetime,
updated: datetime
```

#### Endponts:

- GET /veiculos/find
Retorna todos os veículos

- GET /veiculos/{id}
Retorna os detalhes do veículos

- POST /veiculos
Adiciona um novo veículo

- PUT /veiculos/{id}
Atualiza os dados de um veículo

- PATCH /veiculos/{id}
Atualiza os dados de um veiculo

- DELETE /veiculos/{id}
Apaga o veículo
  
Sua avaliação será analisada por ferramentas de qualidade de código e após isso seu solução passará por um processo de gamificação para atribuição de nota.
