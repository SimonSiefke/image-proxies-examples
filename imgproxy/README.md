# imgproxy

```sh
docker run -p 8080:8080 -it darthsim/imgproxy
```

## Basic Example

- Url: http://source.unsplash.com/random
- Proxy Url: http://localhost:8080/insecure/plain/http://source.unsplash.com/random

## Resize Example

- Url: http://source.unsplash.com/random
- Resize to 300x200
- Proxy Url: http://localhost:8080/insecure/fit/300/200/no/0/plain/http://source.unsplash.com/random

## Memory Usage

- 24.8MB

## Docker install time

- 26.783s

## Docker startup time

- 1.518s

## Smart Crop

- Yes (LibVips)

## License

- MIT

## Docs

- https://docs.imgproxy.net/#/generating_the_url_basic?id=example
