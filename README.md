# Docker log collector

You can see every log in browser.

## How to use

```shell
# Start the container
$ docker-compose up -d
```

Open in the browser: http://localhost:9999

## Configure

You can change the default `9999` port by set `DOZZLE_PORT` environment variable:

```shell
$ DOZZLE_PORT=9876 docker-compose up -d
``` 
