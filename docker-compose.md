# Docker compose commands:

**Obs.:** Com a migração do Docker Compose V1 para Docker Compose V2, a sintaxe recomendada é a utilização da raiz `docker compose`, não mais `docker-compose` como na v1.

- Criar e iniciar um (quando passado "service") ou todos os serviços, parâmetro `-d` usado para liberar o terminal.
```
docker compose up -d "service"
```
 
- 'buildar' e 'rebuildar' um (quando passado "service") ou todos os serviços.
```
docker compose build "service"
``` 

- Criar um (quando passado "service") ou todos os serviços.
```
docker compose create "service"
``` 

- Parar um (quando passado "service") ou todos os serviços.
```
docker compose stop "service"
``` 

- Remover um (quando passado "service") ou todos os serviços.
```
docker compose down "service"
``` 

- Remover imagem utilizada pelo serviço.
```
docker compose down --rmi "service"
```

- Iniciar um (quando passado "service") ou todos os serviços.
```
docker compose start "service"
``` 

- Copiar arquivos e pastas entre container service e filesystem.
```
docker compose cp "src_path" "service":"dest_path"
``` 

- Forçar stop dos serviços.
```
docker compose kill "service"
``` 

- Exibir todos os projetos parados do Compose.
```
docker compose ls -a
``` 

- Pausar serviço.
```
docker compose pause "service"
``` 

- Remover serviço parado.
```
docker compose rm "service"
```

- Atribuir nome ao container.
```
docker compose run --name
```

- Exibir os processos em execução.
```
docker compose top
``` 

- Exibir informações da versão docker compose.
```
docker compose version
```

- Verificar os containers que estão em execução.
```
docker compose ps -a
```

