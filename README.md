# Ape Commerce website

Ape Commerce documentation website using [Hugo](https://gohugo.io) framework with the [Docsy](https://www.docsy.dev) theme.

## Development

Deploy dev stack:

```
docker compose up
```

Get a shell from the Hugo container:

```
docker compose exec hugo bash
```

Build local search index:

```
hugo
```

Start server (http://localhost:1313):

```
hugo server
```
