# Spring-boot-arquitetura
Projeto Java padrão para quem quer desenvolver Web Service Rest (Esse projeto Serve como Projeto Base)

Esse Projeto Roda no próprio tomcat interno.
Pouca Configuração


Quando Baixar basta modificar o application.properties para conectar com o banco de dados que você queira.
Esse exemplo que fiz esta conectado com o Postgres



# DATABASE
spring.datasource.url=jdbc:postgresql://localhost:5432/Nutricao
spring.datasource.username=postgres
spring.datasource.password=admin@123
spring.datasource.driver-class-name=org.postgresql.Driver

# HIBERNATE
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
spring.jpa.properties.hibernate.format_sql=false
spring.jpa.properties.hibernate.show_sql=false
#spring.jpa.hibernate.ddl-auto=create