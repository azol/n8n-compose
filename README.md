# n8n Docker Compose

These instructions cover how to run n8n on a Linux server using Docker Compose.

https://docs.n8n.io/hosting/installation/server-setups/docker-compose/


Set env:

```sh
cp .env.example .env
```

Edit `.env` as needed.


Create local files directory

```sh
mkdir local-files
```

Start n8n by typing:

```sh
docker compose up -d
```

To stop the containers, type:

```sh
docker compose stop
```