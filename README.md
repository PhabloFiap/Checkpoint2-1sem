# Projeto Spring Boot - CRUD com Banco de Dados Oracle

Este é um projeto Spring Boot que demonstra operações básicas de criação (Create) e leitura (Read) usando o Postman para testar a inserção de dados em um banco de dados Oracle. O projeto inclui uma entidade simples com os campos "id", "nome", "classificacao", "tamanho" e "preco".

# Requisitos

* Java 11
* Maven
* Oracle Database
* Postman (ou outra ferramenta similar para testar APIs)

# Endpoints

O projeto expõe os seguintes endpoints:

* POST /localhost:8080/brinquedos: Cria um novo BRINQUEDO no banco de dados. O corpo da solicitação deve ser um JSON contendo os campos necessários (nome, classificacao, tamanho, preco).
![foto do post no postman](https://github.com/PhabloFiap/Checkpoint2-1sem/blob/main/fotos%20do%20projeto/segundo%20post.png)


* GET /localhost:8080/brinquedos: Retorna todos os produtos armazenados no banco de dados.
![foto do create no postman](https://github.com/PhabloFiap/Checkpoint2-1sem/blob/main/fotos%20do%20projeto/get%20com%202%20brinquedos%20add.png)

# Executando o Projeto

1. Clone o repositório para sua máquina local.
2. Configure o banco de dados conforme descrito acima.
3. Execute o projeto usando Maven:
  `mvn spring-boot:run`

# Testando os Endpoints

1. Abra o Postman.
2. Importe a coleção de requisições fornecida no diretório `postman` deste repositório.
3. Execute as solicitações para criar e ler produtos.

# Verificação dos Endpoints no banco de dados Oracle

![abrindo banco de dados sem nenhum post](https://github.com/PhabloFiap/Checkpoint2-1sem/blob/main/fotos%20do%20projeto/verificacao%20oracle.png)
![inserção do Post do java no Oracle](https://github.com/PhabloFiap/Checkpoint2-1sem/blob/main/fotos%20do%20projeto/segunda%20insercao%20bd.png)


# Foto do Initializer do Springboot 

![print do initializer](https://github.com/PhabloFiap/Checkpoint2-1sem/blob/main/fotos%20do%20projeto/springboot%20int.jpg)
# Dependencias do pom.xml
![print das dependencias](https://github.com/PhabloFiap/Checkpoint2-1sem/blob/main/fotos%20do%20projeto/dependencia%20do%20pom.png)
