# Ape Commerce website

Ape Commerce documentation website using [Hugo](https://gohugo.io) framework.

## Setup

To customize the default website local port or UID / GID, create a `.env` file:

```
cp .env.sample .env
```

## Development

Deploy dev stack:

```
docker compose up
```

Get a shell from the Hugo container:

```
docker compose exec hugo bash
```

Start server (http://localhost:8080):

```
hugo server
```
