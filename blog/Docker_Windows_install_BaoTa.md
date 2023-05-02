## PULL and Run Docker images



## PULL Images
1. vist [hub.docker](https://hub.docker.com/) Searching your keyword 
2. On terminal using : docker search "keyword" ,like : docker search java
3. Then run : docker pull centos/cetos-7 , pull it

## Run Images
1. Demo 1
docker run -itd --name my-centos couchbase/centos7-systemd
2. Demo 2
docker run -d --name php-nginx-code5 -p 9998:80 -v /e/docker/sharing/code5:/app  webdevops/php-nginx



