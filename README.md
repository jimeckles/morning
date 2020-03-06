# morning

Spring REST services project.

H2 database, JPA, Spring HTTP MVC, 

# Run 

mvn clean spring-boot:run

curl -v localhost:8080/employees

Create new employee

curl -X POST localhost:8080/employees -H 'Content-type:application/json' -d '{"name": "Samwise Gamgee", "role": "gardener"}'

# Based on 

https://spring.io/guides/tutorials/rest/

https://spring.io/projects/spring-boot

https://start.spring.io/

