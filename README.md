# flask-redis-docker

Two containers running together via Docker Compose. Flask counts page visits, Redis stores the number persistently across restarts.

## Run

```bash
git clone https://github.com/boozer23/flask-redis-docker.git
cd flask-redis-docker
docker compose up --build
```

Open http://localhost:5001

## Stack

Python, Flask, Redis, Docker Compose, Docker Volumes