FROM node

RUN git clone https://github.com/docker-hy/backend-example-docker.git
WORKDIR /backend-example-docker
RUN npm install

ENTRYPOINT [ "npm", "start" ]