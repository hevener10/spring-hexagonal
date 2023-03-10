# Arquitetura Hexagonal/Ports and Adapters NA PRÁTICA

Este é um curso prático que ensina como aplicar a arquitetura hexagonal em microsserviços utilizando Java, Spring Boot, MongoDB e Kafka. A arquitetura hexagonal, também conhecida como Ports and Adapters, é uma abordagem arquitetônica que separa as regras de negócio da implementação técnica, facilitando a manutenção, testabilidade e escalabilidade de um sistema.

Durante este curso, você aprenderá os fundamentos da arquitetura hexagonal e como aplicá-la em microsserviços utilizando as ferramentas Java, Spring Boot, MongoDB e Kafka. Você também aprenderá como testar e implantar microsserviços baseados em arquitetura hexagonal.

Este curso é indicado para desenvolvedores Java que desejam aprender como aplicar a arquitetura hexagonal em microsserviços. Pré-requisitos incluem conhecimento básico em Java e Spring Boot.

Link para o curso: https://www.udemy.com/course-dashboard-redirect/?course_id=4936634

## Instruções de Instalação e Uso

Para utilizar este projeto, siga os seguintes passos:

1. Faça o download do código fonte do projeto a partir do link acima.
2. Certifique-se de ter instalado as ferramentas Java, Spring Boot, MongoDB e Kafka em sua máquina.
3. Configure as credenciais de acesso ao MongoDB e Kafka no arquivo `application.properties`.
4. Compile e execute o projeto utilizando o comando `mvn spring-boot:run`.

Para compilar e empacotar o projeto em um arquivo JAR, execute o seguinte comando:



`mvn package`

Isso irá gerar um arquivo JAR na pasta `target`. Para executar o arquivo JAR, execute o seguinte comando:




`java -jar target/nome-do-arquivo.jar`

Certifique-se de substituir `nome-do-arquivo` pelo nome do arquivo JAR gerado.

Para executar os testes automatizados do projeto, execute o seguinte comando:



`mvn test`

Isso irá executar todos os testes automatizados do projeto e gerar um relatório de cobertura de código na pasta `target/site/jacoco`.

## Documentação

A documentação completa do projeto está disponível no arquivo `docs/README.md`. Este arquivo descreve a estrutura do projeto, as classes e métodos principais, bem como os endpoints da API.

## Contribuindo

Sinta-se à vontade para contribuir com este projeto através de pull requests e issues. Todas as contribuições são bem-vindas e serão avaliadas pelos mantenedores do projeto.

## Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo `LICENSE` para obter mais detalhes.
