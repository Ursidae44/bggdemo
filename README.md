# bggdemo

build image
docker build -t bggdemo .

run image
docker run --rm=true --name bggdemo -p 5000:80 -it bggdemo:latest

ctrl-c to stop container/server, and remove the container afterward



