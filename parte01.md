# Testando microservices: 12 técnicas úteis - Parte 1

## Pontos Principais

* Uma arquitetura de microservices depende mais de dependências remotas e menos de componentes em processo,
por isso, a estratégia e ambientes de testes pricisam se adptar as estas alterações.
* Ao testar monolitos usando técnicas pré-existentes, como a virtualização de serviço, não é necessário
testar tudo de uma vez, podemos dividir o trabalho e testar os módulos individualmente ou em grupos de
componentes que sejam coerentes;
* Ao trabalhar com microservices, existem várias outras opções disponíveis, por que são implantados 
normalmente em ambientes que usam containers com o Docker.
* Pricisaremos gerenciar os componentes interdependetes para testar os microservices de maneira enconômica.
Podemos usar testes duplicados nos teste de microservices que precisam de dependências reais;
* Dependendo das ncessidade, podemos escolher umas das opções listadas neste artigo ou uma combinação delas.