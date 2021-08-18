# Desafio Devops Indra

O objetivo desse desafio é criar uma infraestrutura usando Docker provendo um servidor
Web/PHP e um servidor MySQL.
Requisitos mínimos

Um arquivo README.md deve ser fornecido com todas as instruções necessárias
para execução do projeto.

- A solução deve ser construída usando Docker.
- O servidor web deve estar disponível na porta 8080.
- O servidor web (Apache, Nginx ou qualquer outro) deve conter as dependências necessárias para conexão do PHP ao MySQL disponíveis.
- O container do servidor web deve ser capaz de conectar-se ao container do servidor
MySQL.

## Pontos extras: 

- Se a solução oferecer um arquivo docker-compose.yml
- Se o container do servidor MySQL persistir os dados em um volume.
- Se a senha do usuário root do MySQL for a seguinte: GAud4mZby8F3SD6P

- Apesar de ser permitido uso de uma imagem pública que contenha as
dependências já instaladas, é considerado um grande diferencial se for fornecido
um arquivo Dockerfile para o servidor web.

- Se durante o processo de criação do container MySQL o arquivo de backup
sample-db.sql for restaurado.

Se o arquivo index.php estiver disponível no servidor web e conectando-se ao
banco de dados. Esse usa variáveis de ambiente para conectar-se ao banco,
portanto depende que as variáveis ​MYSQL_ROOT_PASSWORD​, ​MYSQL_HOST​ e
MYSQL_PORT​ estejam definidas e que o arquivo sample-db.sql tenha sido restaurado
como descrito no item anterior.
