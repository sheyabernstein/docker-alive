
## Docker Alive

| [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) | [![Lint](https://github.com/sheyabernstein/docker-alive/actions/workflows/lint.yml/badge.svg?branch=main)](https://github.com/sheyabernstein/docker-alive/actions/workflows/lint.yml) | [![Publish](https://github.com/sheyabernstein/docker-alive/actions/workflows/publish.yml/badge.svg)](https://github.com/sheyabernstein/docker-alive/actions/workflows/publish.yml) |
|----------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

A lightweight container to monitor a docker host written in Go.

### Usage

```bash
docker run --name alive -d -p 4444:4444 sheyabernstein/alive:latest
```

Alternatively, use the included docker-compose file.
### API Reference

#### Liveness

```http
GET /liveness
```

Returns HTTP 200 OK
## License

[MIT](https://choosealicense.com/licenses/mit/)
