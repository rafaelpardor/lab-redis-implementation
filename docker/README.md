# Basic Redis with Docker

```bash
docker run --rm --name some-redis redis:latest
docker exec -it some-redis redis-server
docker exec -it some-redis redis-cli
```
