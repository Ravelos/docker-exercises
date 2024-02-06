# docker-exercises
# Docker commands:

``` docker create [options] “image” ``` Cria um container a partir da imagem.

- `docker ps`: Contenedores que estão em execução.
  
- `docker ps -a`: Lista de todos os container.
  
- `docker rm "container_id"`: Remover container.

- `docker rm "container_name"`: Remover container.

- `docker start "container_name"`: Subir um container.

- `docker stop "container_name"`: Parar um container.

- `docker top`: Exibe os processos rodando em um container.

- `docker restart "container_name"`: Reinicia um container que está em pause.

- `docker kill "container_name"`: Da Poweroff no container.

- `docker pause "container_name"`: Pausa o container.

- `docker unpause "container_name"`: Inicia um container que está rodando ou parado.

- `docker exec [options] "container_name"`: Executa instrução dentro do container que está rodando sem precisar ‘atachar’.

- `docker attach "container_name"`: Acesso ao container para alterações.

- `docker wait "container_name"`: Aguarda o retorno da execução de um container para iniciar esse container.

- `docker cp "src_path" "container_name":"dest_path"`: Copia arquivos ou diretórios do container para o host.

- `docker diff "container_name"`: Exibe as alterações feitas no filesystem do container.

- `docker events`: Exibe os eventos do container em tempo real.

- `docker history "image"`: Exibe o histórico de comandos executados dentro do container.

- `docker inspect --type "container_name"`: Exibe o json com todas as configurações do container.

- `docker rename "container_name" "new_container_name"`: Renomeia um container existente.

