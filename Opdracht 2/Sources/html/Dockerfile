# Showcase OSS
# OSS - no tag

FROM nginx:stable-alpine
LABEL author = Johannes Sim / Renzo Veldkamp
ENV REFRESHED_AT 2017-12-06

COPY  index.html *.png /usr/share/nginx/html/

COPY  nginx.conf /etc/nginx/nginx.conf

# build:  docker build -t centricms/opdracht2_html .
# run:    docker run --name opdracht2_html --network="opdracht2-network" -d -p 4200:80 -p 8080:8080 centricms/opdracht2_html
# run centric config: docker run --name opdracht2_html -v C:/Data/GitRepos/MicroContainer/OSS/html/conf:/etc/nginx/conf.d/:ro -d -p 4200:80 centricms/opdracht2_html
# delete: docker rm -f  centricms/opdracht2_html
# push:   docker push centricms/opdracht2_html
# pull:   docker pull centricms/opdracht2_html
# in:     docker exec -it centricms/opdracht2_html /bin/sh