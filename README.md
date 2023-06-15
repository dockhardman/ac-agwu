# ac-agwu

docker run -itd \
    -n ac-nginx-ui \
    -v /home/nginxWebUI:/home/nginxWebUI \
    -e BOOT_OPTIONS="--server.port=8080" \
    --privileged=true \
    --net=host \
    cym1102/nginxwebui:latest
