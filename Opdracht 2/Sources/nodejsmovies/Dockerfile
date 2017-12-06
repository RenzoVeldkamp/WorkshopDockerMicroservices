# Showcase OSS
# nodejsmovies - no tag

FROM node:8-alpine
LABEL author = Johannes Sim / Renzo Veldkamp
ENV REFRESHED_AT 2017-12-06

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Bundle app source
COPY . /usr/src/app/

# Install app dependencies
RUN npm install

CMD [ "npm", "run", "movies" ]

# build:  docker build -t centricms/opdracht2_nodejsmovies .
# run:    docker run --name opdracht2-api --network="opdracht2-network" -d -p 8090:80 centricms/opdracht2_nodejsmovies
# delete: docker rm -f opdracht2_nodejsmovies
# push:   docker push centricms/opdracht2_nodejsmovies
# pull:   docker pull centricms/opdracht2_nodejsmovies
# in:     docker exec -it opdracht2_nodejsmovies /bin/sh