<a href="https://snapcraft.io/redis">
	<img alt="redis" src="https://snapcraft.io/redis/badge.svg"/>
</a>
<br>
<img src="https://github.com/AzagraMac/redis-docker/assets/571796/5316f9a7-c956-4226-8619-2c913897c3d0" width="400">

## Build

    git clone https://github.com/AzagraMac/redis-docker.git
    cd redis-docker
    
    docker build -t yourname/redis:tag


## Launch

    docker compose up -d

## Loggin

    docker logs -f redis
