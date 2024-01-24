# Sistema de Gerenciamento de Pedidos 🛒 📦

Este é um projeto simples de um sistema de gerenciamento de pedidos, desenvolvido como parte do estudo em Java com o framework Spring Boot. O sistema possui entidades como Usuário, Pedido, Produto, Categoria, Pagamento e Pedido do Item. 

Este projeto foi desenvolvido por Danilo Garcia Paravani.

## Tecnologias Utilizadas
- Java
- Spring Boot
- H2 Database (para ambiente de teste)
- JPA/Hibernate
- Maven
- Postman

## Como Rodar o Projeto
1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/DaniloParavani/workshop-springbot3-jpa.git

2. No terminal, navegue até o diretório do projeto:

3. Certifique-se de ter o Maven instalado. Execute o seguinte comando para compilar e construir o projeto:
   ```bash
   mvn clean install

4. Após a construção, você pode executar o aplicativo Spring Boot usando o seguinte comando:
   ```bash
   mvn spring-boot:run

A aplicação estará acessível em http://localhost:8090

5. Para acessar o console H2 para verificar os dados do banco de dados, vá para http://localhost:8090/h2-console. Username: sa | Password não é necessário.

## Endpoints da API

### Usuários

- GET /users: Retorna todos os usuários.
- GET /users/{id}: Retorna um usuário específico.
- POST /users: Cria um novo usuário.
- DELETE /users/{id}: Exclui um usuário.
- PUT /users/{id}: Atualiza os dados de um usuário existente.

  #### Exemplo de body para os métodos POST e PUT
  
  ![image](https://github.com/DaniloParavani/workshop-springbot3-jpa/assets/87047957/a03cac41-c036-42a6-9448-aa315d814bb5)

### Pedidos

- GET /orders: Retorna todos os pedidos.
- GET /orders/{id}: Retorna um pedido específico.

### Produtos

- GET /products: Retorna todos os produtos.
- GET /products/{id}: Retorna um produto específico.

### Categorias

- GET /categories: Retorna todas as categorias.
- GET /categories/{id}: Retorna uma categoria específica.
