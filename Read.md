docker exec -it -u root {{docker container id}} apk add --no-cache ffmpeg  --install ffmpeg

docker exec -it {{docker container id}} ffmpeg -version  --check version

docker exec -it -u root 174e08280690 bash --macos
apt update && apt install -y ffmpeg -- install ffmpeg
ffmpeg -version