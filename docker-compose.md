# Docker compose commands:

**Obs.:** Com a migração do Docker Compose V1 para Docker Compose V2, a sintaxe recomendada é a utilização da raiz `docker compose`, não mais `docker-compose` como na v1.

- `docker compose up -d "service"`: criar e iniciar um (quando passado "service") ou todos os serviços, parâmetro `-d` usado para liberar o terminal.
 
- `docker compose build "service"`: 'buildar' e 'rebuildar' um (quando passado "service") ou todos os serviços.

- `docker compose create "service"`: criar um (quando passado "service") ou todos os serviços.

- `docker compose stop "service"`: parar um (quando passado "service") ou todos os serviços.

- `docker compose down "service"`: remover um (quando passado "service") ou todos os serviços.

- `docker compose down --rmi "service"`: remover imagem utilizada pelo serviço.

- `docker compose start "service"`: iniciar um (quando passado "service") ou todos os serviços.

- `docker compose cp "src_path" "service":"dest_path"`: copiar arquivos e pastas entre container service e filesystem.

- `docker compose kill "service"`: forçar stop dos serviços.

- `docker compose ls -a`: exibir todos os projetos parados do Compose.

- `docker compose pause "service"`: pausar serviço.

- `docker compose rm "service"`: remover serviço parado.

- `docker compose run --name`: atribuir nome ao container.

- `docker compose top`: exibir os processos em execução.

- `docker compose version`: exibir informações da versão docker compose.

- `docker compose ps -a`: verificar os containers que estão em execução.

