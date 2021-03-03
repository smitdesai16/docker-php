# docker-php

## Development Run
```bash
php index.js
```

## Docker Run
```bash
docker build -t docker-php .
docker run -p 8080:80 -d docker-php
```