# Primeiros passos no Spring
 > Primeiro tutorial de Spring e Spring Boot pela trilha de programação do Instituto Caldeira

O início do projeto foi feito com o [Spring Initializr](https://start.spring.io/), usando a IDE da JetBrains para o Java, o [Intellij](https://www.jetbrains.com/idea/promo/?msclkid=fabce1580fcf17f364c8841a430c80c5&utm_source=bing&utm_medium=cpc&utm_campaign=AMER_en_BR_IDEA_Branded&utm_term=intellij&utm_content=intellij%20idea).

## Requisitos
- [Java 17](https://www.oracle.com/java/technologies/downloads/#java17)
- [Gradle 8.3](https://gradle.org/install/)

> Lembrando que com o uso do Intellij, você tem um ambiente mais facilitado sem a necessidade de fazer downloads manuais dos gerenciadores de dependencias (tanto [Gradle](https://gradle.org/install/), como [Maven](https://maven.apache.org/install.html)).

<br>

### Rodando na sua máquina
- Faça o clone do repositório
- Abra em sua IDE de preferência
- Rode o comando MacOs/Linux: ```./gradlew bootRun```
- Windows: ```.\gradlew.bat bootRun```<br><br>
> Após isso, digite no seu navegador ```http://localhost:8080/hello```

<br>

### O que tem nos repositorios?
Aqui foi simplesmente feito um projeto Inicial do Spring através do [QuickStart](https://spring.io/quickstart).<br>
Vou destacar aqui:
- Uso das annotations, mostrando como o Spring facilita e muito o desenvolvimento.
- O proprio uso do framework já poupa muitas linhas de código
- Com um simples ```main``` e alguns ```imports``` já temos nosso projeto rodando na web. 
