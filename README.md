# Zero 2 Production

Repository while working through the book Zero 2 Production




## Postgres

Run Postgres in a Docker container 

```sh
docker compose -f ./scripts/postgres_docker_compose.yaml up -d 
```

Shut down Docker compose 

```sh
docker compose -f ./scripts/postgres_docker_compose.yaml down
```

Install `psql`

```sh
sudo dnf install postgresql-contrib
```

Install sqlx-cli

```sh
cargo install --version=0.5.7 sqlx-cli --no-default-features --features postgres
```

#### Reference

- [zero2prod repository](https://github.com/LukeMathWalker/zero-to-production)
