# Showcase OSS
# OSS - no tag

FROM nginx:stable-alpine
LABEL author = Johannes Sim / Renzo Veldkamp
ENV REFRESHED_AT 2017-12-06

COPY  index.html *.png /usr/share/nginx/html/

COPY  nginx.conf /etc/nginx/nginx.conf

# build:  docker image build -t centricms/opdracht2-html .
# run:    docker container run --name opdracht2-html --network="opdracht2-network" -d -p 4200:80 -p 8080:8080 centricms/opdracht2-html
# run centric config: docker run --name opdracht2-html -v C:/Data/GitRepos/MicroContainer/OSS/html/conf:/etc/nginx/conf.d/:ro -d -p 4200:80 centricms/opdracht2_html
# delete: docker container rm -f  centricms/opdracht2-html
# push:   docker image push centricms/opdracht2-html
# pull:   docker image pull centricms/opdracht2-html
# in:     docker exec -it centricms/opdracht2-html /bin/sh