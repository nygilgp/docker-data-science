# Docker for Data Science

## Build
    docker build -t docker-data-science .

## Run
    docker run --name docker-data-science -p 8888:8888 -v "$PWD/notebooks:/opt/notebooks" -d docker-data-science

## Stop
    docker rm -f docker-data-science

