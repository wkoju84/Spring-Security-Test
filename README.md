<h1 align="center"># Spring-Security-Test</h1>

API simples para teste de implementação do Spring Security

## Tecnologias

- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring Security](https://spring.io/projects/spring-security)
- [Spring MVC](https://docs.spring.io/spring-framework/reference/web/webmvc.html)
- [Spring Data JPA](https://spring.io/projects/spring-data-jpa)


## Como Executar Este Projeto:

- Clonar repositório git
- Construir o projeto:
```
$ ./mvnw clean package
```
- Executar a aplicação:
```
$ java -jar target/SpringSecurity-0.0.1-SNAPSHOT.jar
```
- Executar a aplicação usando Docker:
```
Com o docker instalado:

docker build -t spring-security-test .

docker run -p 9000:9000 [nome da imagem]

```

A API poderá ser acessada em [localhost:9000/login](http://localhost:9000/login).

## API endpoints

localhost:9000/login

login de usuário: gto.onizuka@sensei.com
senha: password

login de admin: minks@sensei.com
senha: password2