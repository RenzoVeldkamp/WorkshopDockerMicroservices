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

# build:  docker image build -t centricms/opdracht2-nodejsmovies .
# run:    docker container run --name opdracht2-api --network="opdracht2-network" -d -p 8090:80 centricms/opdracht2-nodejsmovies
# delete: docker container rm -f opdracht2-nodejsmovies
# push:   docker image push centricms/opdracht2-nodejsmovies
# pull:   docker image pull centricms/opdracht2-nodejsmovies
# in:     docker exec -it opdracht2-nodejsmovies /bin/sh