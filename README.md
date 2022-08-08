# Email-microservice

Microsserviço de Email desenvolvido em um treinamento da Michelli Brito.

Aula prática de como criar um microservice para envio de email com Spring Boot e Spring Mail(Com o email e senha gerada por cada usuário).
ir em resources, e colocar eles em: 

spring.mail.username=******@gmail.com
spring.mail.password=****************

A conexão com a instância do RabbitMQ também ficou em resources com os seguintes atributos: Endereço obtido na criação da instância e nome da fila
spring.rabbitmq.addresses=*********************
spring.rabbitmq.queue=*******


O objetivo do treinamento é mostrar como o serviço de email trabalha de forma independente e autônoma dentro da arquitetura exercendo seu papel específico que é o envio de email com sua base isolada. 
Para que os microsservices se comunicarem de forma assíncrona, foi criada uma instância da mensageria RabbitMQ.

# Tecnologias utilizadas
* Java
* Spring Boot
* Spring Mail
* JPA / Hibernate
* Maven
* RabbitMQ
* Postgresql
```
# Clonar repositório
git clone https://github.com/CarlosDaniel396/email-microservice.git

# executar o projeto
./mvnw spring-boot:run

```
