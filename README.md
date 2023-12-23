# Welcome to Docker

## Building

Build and run:

```bash
docker build -t welcome-to-docker . 
docker run -d -p 8088:3000 --name welcome-to-docker welcome-to-docker
```

Open `http://localhost:8088` in your browser.

## Maintenance

Maintainers should see [MAINTAINERS.md](MAINTAINERS.md).