ympd https://github.com/notandy/ympd MPD web client running in a Docker image.

```Bash
docker run --name my-ympd -d -p 8080:8080 --link mpd_container:mpdhost knapoc/docker-ympd
```

Browse to http://localhost:8080/

Forked from [alastairhm/docker-ympd](https://github.com/alastairhm/docker-ympd).