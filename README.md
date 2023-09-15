# NOSQL
Objetivo desse repositório criar um case para trabalhar banco de dados não relacional MONGODB
![image](https://github.com/TatianaFlorentino/NOSQL/assets/41309689/1b06acc3-7244-4c8d-a5df-efbba28657af)

* [Introdução MongoDB.](#introducao-MongoDB)  
* [Descrição do Projeto](#descrição-do-projeto)  
* [Status do Projeto](#status-do-Projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Contribuidoras](#pessoas-contribuidoras)
* [Etapas](#Etapas)
* [Conclusão](#conclusão)

## Introdução MongoDB
No NoSQL e MongoDB: entendendo o que é NoSQL e as principais características do MongoDB.
Primeiros passos: configurando o ambiente e executando os primeiros comandos.
Gerenciamento Básico: Gerenciar usuários, analisar execuções de scripts, importação de dados, backup e restauração, além de gestão de MongoDB na nuvem da AWS com Atlas.
CRUD – Create, Read, Update & Delete: comandos elementares para consulta e manipulação de dados no MongoDB.
Modelagem de Dados: os fundamentos da modelagem de dados orientada à documentos em um case comparativo com modelagem relacional, além de padrões profissionais de modelagem.

Cenário de Aprendizado: Criando um Catálogo de Livros com MongoDB

Objetivo: Conceitos básicos do MongoDB criando um catálogo de livros simples.

# Etapas para realizar o projeto:

Configuração do Ambiente:

* Criação de um conta MongoDB Atlas,ou seja, nuvem que oferece uma versão gratuita para fins de aprendizado.
![image](https://github.com/TatianaFlorentino/NOSQL/assets/41309689/0c7fdd33-2637-4ea3-9c5f-402cc34feddc)
Caso você escolha trabalhar com NoSQL - MongoDB Atlas na nuvem a interface gráfica permite você criar database, gerenciar usuários, resetar consultas tudo de forma gráfica UI, você precisa apenas de alguns conceitos básicos para começar a usar a ferramenta.[Documentação e Recursos de referências](https://www.mongodb.com/docs/manual/reference/database-references/)
Existe um material bem interessante sobre o assunto YouTube que mostra passo a passo em português para iniciar 

Porém como ideia aqui é explorar mais afundo os comandos, acho melhor instalar MongoDB local.
Importante salientar que é indicado o conhecimento de alguma linguagem de programação.
Como meu objetivo e trabalhar com consultas NoSQL, optei pela arquitetura local.


* Criando o Banco de Dados com Python:

* Iniciando o servidor MongoDB.
  Abrindo um terminal ou cliente de linha de comando e conecte-se ao servidor MongoDB.
Comandos utilizados no mongoDB:

```show dbs```

```use norelacional```

```show collections```

Criando um novo banco de dados para o seu catálogo de livros, por exemplo, "livraria".

Criando uma Coleção:
```db.createCollection("livraria");```

* Dentro do banco de dados, crie uma coleção chamada "livros".

As coleções no MongoDB são equivalentes a tabelas em bancos de dados relacionais.
Inserindo Documentos:

* Bora inserir alguns documentos (dados) na coleção "livros". Cada documento pode representar um livro e incluir campos como "título", "autor" e "ano de publicação".
Utilize comandos como insertOne ou insertMany para adicionar dados à coleção.
Consultando Documentos:

* Explorando comandos de consulta para recuperar informações sobre os livros em sua coleção. Usando find para recuperar todos os documentos ou findOne para encontrar um livro específico.
Atualizando Documentos:

* Experimentando atualizar um ou mais documentos na coleção. Por exemplo, você pode alterar o título ou o autor de um livro.
Excluindo Documentos:

* Praticando a exclusão de documentos da coleção. Usando o comando deleteOne ou deleteMany para remover livros específicos ou vários de uma só vez.



* Avaliando como usar índices, agregações e indexação geoespacial.

## Descrição do Projeto
Crawler com MongoDB

## Status do Projeto

## Funcionalidades e Demonstração da Aplicação

## Acesso ao Projeto

## Tecnologias utilizadas

## Pessoas Contribuidoras

## Etapas

## Conclusão

Conclusão : Esse case tem uma base sólida para entender os conceitos básicos do MongoDB, como armazenar, recuperar, atualizar e excluir dados de um cluster, como gerenciar um banco de dados não relacional na nuvem, modelagem de dados que é importante avaliar esses conceitos para arquiteturas de dados hibridas ( modelo relacional Vs Não relacional), e fechando um case pegando dados de documentos da Web e gravando noSQL.Ponto importante avaliação de índices, agregações 

Próximos Passos:  Explorar casos de uso mais complexos com integração do MongoDB e e indexação geoespacial.

Palavras-Chaves: #NOSQL | #MONGODB | Python
