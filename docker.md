# docker-exercises
# Docker commands:

- Cria um container a partir da imagem.
``` 
docker create [options] “image”
``` 

- Contenedores que estão em execução.
```
docker ps
``` 
  
- Lista de todos os container.
```
docker ps -a
``` 
  
- Remover container.
```
docker rm "container_id"
```
  
- Remover container.
```
docker rm "container_name"
```

- Subir um container.
```
docker start "container_name"
```

- Parar um container.
```
docker stop "container_name"
``` 

- Exibe os processos rodando em um container.
```
docker top
```

- Reinicia um container que está em pause.
```
docker restart "container_name"
``` 

- Da Poweroff no container.
```
docker kill "container_name"
``` 

- Pausa o container.
```
docker pause "container_name"
``` 

- Inicia um container que está rodando ou parado.
```
docker unpause "container_name"
``` 

- Executa instrução dentro do container que está rodando sem precisar ‘atachar’.
```
docker exec [options] "container_name"
``` 

- Acesso ao container para alterações.
```
docker attach "container_name"
``` 

- Aguarda o retorno da execução de um container para iniciar esse container.
```
docker wait "container_name"
```

- Copia arquivos ou diretórios do container para o host.
```
docker cp "src_path" "container_name":"dest_path"
``` 

- Exibe as alterações feitas no filesystem do container.
```
docker diff "container_name"
``` 

- Exibe os eventos do container em tempo real.
```
docker events
``` 

- Exibe o histórico de comandos executados dentro do container.
```
docker history "image"
``` 

- Exibe o json com todas as configurações do container.
```
docker inspect --type "container_name"
```

- Renomeia um container existente.
```
docker rename "container_name" "new_container_name"
``` 

