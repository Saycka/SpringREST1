# SpringREST1

запуск jar: spring-boot:run

для war 
1. добавлен класс ServletInitializer
2. в pom добавлено <packaging>war</packaging>
3. в pom 
<dependency>
<groupId>org.springframework.boot</groupId>
<artifactId>spring-boot-starter-test</artifactId>
<scope>test</scope>
</dependency>
заменено на
<dependency>
<groupId>org.springframework.boot</groupId>
<artifactId>spring-boot-starter-tomcat</artifactId>
<scope>provided</scope>
4. класс Application не нужен? (отработало без него)