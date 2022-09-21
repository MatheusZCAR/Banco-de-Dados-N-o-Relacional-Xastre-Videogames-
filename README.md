# Banco-de-Dados-Nao-Relacional-Xastre-Videogames-
Trabalho de montagem de um Banco de Dados Não Relacional (Json, Docker e MongoDB)
Temos que atraves do docker file, puxar nossa database do git, enviar para nosso container, e qualquer modificação devemos retornar para o git
mongo-express local - docker run -d -p 8081:8081 -e ME_CONFIG_MONGODB_SERVER=host.docker.internal -e ME_CONFIG_MONGODB_PORT=49153 -e ME_CONFIG_MONGODB_ADMINUSERNAME=docker -e ME_CONFIG_MONGODB_ADMINPASSWORD=mongopw --name mongo-express mongo-express
