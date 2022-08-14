# Photoprism

Para rodar você precisa ter o docker instalado
Você encontra ele [aqui](https://docs.docker.com/desktop)

Após baixar o docker baixe esse projeto adicione suas fotos a pasta pictures e execute:

```bash
docker-compose up -d && docker-compose exec photoprism photoprism index -f
```

Após terminar a indexação dos arquivos acesso o Photoprism por [aqui](http://localhost:2342)

Para acesso via celular utilize o [Photosync](https://photosync-app.com)