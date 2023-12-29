# Ape Commerce documentation website

Documentation website for [Ape Commerce](https://github.com/ApeCommerce) using [Hugo](https://gohugo.io) framework with the [Docsy](https://www.docsy.dev) theme.

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

Start dev server:

```
hugo server
```
