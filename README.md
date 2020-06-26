This is a docker image for [Code Maat](https://github.com/adamtornhill/code-maat).

## Build

```bash
docker build -t code-maat .
```

## Run

```bash
docker run --rm -v ~/<path>/<to>/<code>:/codemaat code-maat -l /codemaat/evo.log -c git -a summary
```
