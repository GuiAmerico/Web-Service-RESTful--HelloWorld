# Construindo um Web Service RESTful
Este guia orienta você no processo de criação de um serviço web RESTful “Hello, World” com Spring.
### O que você vai construir:

Você construirá um serviço que aceitará solicitações HTTP GET em ```http://localhost:8080/greeting.```

Ele responderá com uma representação JSON de uma saudação, como mostra a listagem a seguir:

``` {"id":1,"content":"Hello, World!"} ```

Você pode personalizar a saudação com um parâmetro opcional ```name``` na string de consulta, como mostra a lista a seguir:

``` http://localhost:8080/greeting?name=User ```

O ```name ``` valor do parâmetro substitui o valor padrão de ``` World ``` e é refletido na resposta, como mostra a listagem a seguir:

```{"id":1,"content":"Hello, User!"}```

### O Que Você Precisa:

- Cerca de 15 minutos

- Um editor de texto ou IDE favorito

- JDK 1.8 ou posterior

- Gradle 4+ ou Maven 3.2+

- Você também pode importar o código diretamente para o seu IDE:

  - Spring Tool Suite (STS)

  - INtelliJ IDEA
