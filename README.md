Host Server :

Run docker directly

docker pull ghcr.io/shanefagan/mindustry_server/mindustry_server:latest

docker run -ti -p 6567:6567/tcp -p 6567:6567/udp ghcr.io/shanefagan/mindustry_server/mindustry_server:latest

or use docker-compose with the file from the repo

docker-compose up -d 
