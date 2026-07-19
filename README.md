# PhotoPrism

Instale o [Docker Desktop](https://docs.docker.com/desktop/), adicione suas fotos à
pasta `pictures` e execute:

```sh
docker compose up -d
docker compose exec photoprism photoprism index -f
```

Após a indexação, acesse o [PhotoPrism](http://localhost:2342).

Para acesso pelo celular, use o [PhotoSync](https://photosync-app.com).
