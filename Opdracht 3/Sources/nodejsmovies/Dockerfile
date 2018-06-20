# Showcase OSS
# nodejsmovies - no tag

FROM node:8-alpine
MAINTAINER Johannes Sim / Renzo Veldkamp
ENV REFRESHED_AT 2017-09-01

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Bundle app source
COPY . /usr/src/app/

# Install app dependencies
RUN npm install

CMD [ "npm", "run", "movies" ]

# build:  docker image build --no-cache -t centricms/nodejsmovies .
# run:    docker container run --name nodejsmovies -d -p 8090:4201 centricms/nodejsmovies
# delete: docker container rm -f nodejsmovies
# push:   docker image push centricms/nodejsmovies
# pull:   docker image pull centricms/nodejsmovies
# in:     docker image exec -it nodejsmovies /bin/sh