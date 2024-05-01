# API Usuários

A API Usuários é uma aplicação Spring Boot que oferece funcionalidades de autenticação. Além disso, ela está integrada à [API de Clientes](https://github.com/Lucas-dev23/apiClientes). Esta API Usuários utiliza o banco de dados MySQL.

## Pré-requisitos

Antes de iniciar, certifique-se de ter os seguintes requisitos instalados:

- Java JDK 17
- Maven
- Spring Boot
- MySQL 
- Lombok configurado corretamente na sua IDE.

### Configuração do Lombok na IDE

Certifique-se de que o Lombok esteja configurado corretamente na sua IDE. O Lombok é uma ferramenta de produtividade que reduz a verbosidade do código Java, permitindo a criação de classes Java com menos código boilerplate.

Para configurar o Lombok na sua IDE:

1. Faça o download do Lombok JAR a partir do [site oficial do Lombok](https://projectlombok.org/download).
2. Execute o JAR baixado (`lombok.jar`), selecionando a IDE que você está utilizando.
3. Siga as instruções fornecidas para completar a instalação e configuração do Lombok na sua IDE.


## Configuração do Banco de Dados

1. **Criação do Banco de Dados:**

   Crie um banco de dados no MySQL para ser utilizado pelo projeto. Você pode nomeá-lo como preferir, mas recomenda-se utilizar um nome significativo, como `bd_apiusuarios`.

2. **Configuração da Senha em `application.properties`:**

   No arquivo `application.properties`, você encontrará as configurações do seu banco de dados. Certifique-se de alterar a senha para a que você configurou no MySQL. Isso garantirá que a aplicação possa se conectar ao banco de dados corretamente.


## API de Clientes

Esta API de Usuários está integrada com a [API de Clientes](https://github.com/Lucas-dev23/apiClientes), fornecendo serviços de criar, consultar, atualizar e excluir. Embora a API de Usuários funcione independentemente da API de Clientes, utilizar ambas proporcionará uma experiência mais completa.


## Clientes Web

A interface de usuário (UI) desta API foi desenvolvida em Angular e está disponível em: [Clientes Web](https://github.com/Lucas-dev23/clientesWeb). No entanto, para utilizá-la, também é necessário ter a [API de Clientes](https://github.com/Lucas-dev23/apiClientes). 


## Gerando a Tabela no Banco de Dados

Esta aplicação irá gerar as tabelas necessárias no banco de dados automaticamente assim que você rodar o projeto graças ao Hibernate.
