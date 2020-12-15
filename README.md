## Modelagem conceitual e implementação

Estudo de caso do curso Modelagem de Dados UML (Análise&Projeto Orientado a Objetos) da [Udemy](https://www.udemy.com/course/uml-diagrama-de-classes/), com objetivo de implementar um modelo conceitual sobre o paradigma orientado a objetos utilizando Java com Spring Boot e JPA

### :dart: Objetivo

Construir um API Rest de um modelo conceitual, disponibilizando end points para consulta de um sistema básico de pedidos com os respectivos papéis associados na UML

### :bookmark_tabs:Tópicos abordados

- Leitura e entendimento do diagrama de classes
- Leitura e entendimento do diagrama de objetos
- Associações
- Um para muitos / muitos para um
- Um para um
- Muitos para muitos
- Conceito dependente
- Classe de associação
- Herança
- Enumerações
- Tipos primitivos (ItemPedidoPK)
- Entidades fracas (ElementCollection)
- Associações direcionadas

### :pushpin: Pré requisitos 

- Java 8 ou superior
- Spring Tool Suite 
- Banco de dados H2
- Postman 

### Diagrama de classe

<p>
    <img src="https://raw.githubusercontent.com/cernandes/curso-modelagem-conceitual-java/master/assets/img/uml-diagrama.JPG">
</p>

### Diagrama de objetos

<p>
    <img src="https://raw.githubusercontent.com/cernandes/curso-modelagem-conceitual-java/master/assets/img/object-diagrama.JPG">
</p>

### :rocket: Rest
|End point| Dados |
|---------|------|
|/categorias/{id}|Categoria e seus produtos|
|/clientes/{id}| Cliente, seus telefones e seus endereços|
|/pedidos/{id}| Pedido, seu cliente, seu pagamento, seus itens de pedido, seu endereço de entrega|

### :zap: Autor

@[cernandes](https://github.com/cernandes)

### :book: Referência

Modelagem de Dados UML (Análise&Projeto Orientado a Objetos) [Udemy](https://www.udemy.com/course/uml-diagrama-de-classes/)




