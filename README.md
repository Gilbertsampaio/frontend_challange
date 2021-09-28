
# B2B Stack - Engenheiro Frontend

## Objetivo:
* Você deverá implementar uma pequena webapp com SCROLL INFINITO baseado na lista de produtos da página de subcatgegorias (https://portal.hml.b2bstack.com.br/categoria/pre-vendas) do portal B2B Stack.
* O sistema deverá ser uma Single Page Application (SPA) utilizando tecnologias web HTML, JavaScript e CSS.(Não pode ser usado frameworks como VUE, React, Angular, etc)

* A aplicação deve fazer uma requisição para a API de produtos que se encontra na seguinte URL: ```https://portal.hml.b2bstack.com.br/api/v1/products``` 
* A respota da API será um Array no formato JSON:
Onde, `name` é o nome do produto, `average_note` é o NPS do produto, `reviews_counter` é a quantidade de avaliações que o produto recebeu, `rating` é a nota média dada pelo algoritimo B2B Stack e `imagePath` é a url da imagem do logo do produto.
```
[
  {
    "name": "HubSpot",
    "average_note": 4.08,
    "reviews_counter": 36,
    "rating": 4.2,
    "imagePath": "https://s3.amazonaws.com/beta-img.b2bstack.net/produto/hubspot.png"
  }
]
```
A API suporta paginação, onde vc deve enviar o parametro page e o número da página.(Itens por pagina default = 5)
Caso o parametro page não seja enviado, a API retorna um ARRAY com 30 elementos:

## Execução e entrega
Você deve enviar o código em um repositório GIT de sua preferência. Você precisa incluir um arquivo README explicando como devemos fazer para executar o seu código.

## O que será avaliado?
* Técnicas utilizadas para resolver o problema;
* Responsividade e match com as telas de exemplo;
* A forma que você organiza o seu código;
* Legibilidade;
* Arquitetura proposta;
* Boas práticas de Javascript e CSS.
