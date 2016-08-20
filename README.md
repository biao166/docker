docker run -d -P --name deve  biao166/docker

docker run -d -P -h dev --name local-deve -v /Users/biao166/develop:/home/biao166/works  docker_dev



ZSH_THEME="robbyrussell"

docker-compose build
docker-compose pull
docker-compose up -d
