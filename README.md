# Banco-de-Dados-Nao-Relacional-Xastre-Videogames
Trabalho de montagem de um Banco de Dados Não Relacional (Json, Docker e MongoDB)<br />

Para executar o Banco de Dados MONGODB em sua máquina, baixe o arquivo .zip da release, faça a extração em sua área de trabalho e siga as seguintes instruções:<br />

1 - Copie o caminho da pasta extraída<br />
2 - Abra o terminal e execute o comando: "docker run -v <colar o caminho>:/data/db mongo"<br />
3 - Abra outro terminal (sem fechar o anterior) e obtenha o ID do container com o comando: "docker container ls"<br />
4 - Execute o comando: "docker exec -it <ID obtido> bash"<br />
5 - Digite "mongosh" e pressione enter<br />
6 - A partir deste momento, o usuário estará no ambiente MONGODB, com o comando "show dbs" será possível observar as databases presentes.<br />
7 - Para entrar em uma database, utilize o comando "use <nome da database>"<br />
8 - Agora, o usuário poderá buscar por informações do DB com o comando find (no banco de dados feito, temos informações de: "Console", "Vendas", "DataDeLancamento" e " JogoMaisVendido".
