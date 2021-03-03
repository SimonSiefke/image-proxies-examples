# Caravaggio

```sh
docker run --name caravaggio -p 8565:8565 -ti ramielcreations/caravaggio
```

## Basic Example

- Url: http://source.unsplash.com/random
- Proxy Url: http://localhost:8565/?image=http://source.unsplash.com/random

## Resize Example

- Url: http://source.unsplash.com/random
- Resize to 300x200
- Proxy Url: http://localhost:8565/rs,s:300x200?image=http://source.unsplash.com/random

## Memory Usage

- 25MB

## Docker install time

- 22.266s

## Docker Startup time

- 2.045s

## License

- Free to use for non-commercial purpose.

## Docs

- https://docs.imgproxy.net/#/generating_the_url_basic?id=example
