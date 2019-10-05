FROM node

RUN apt-get update && apt-get install -y git
RUN git clone https://github.com/docker-hy/frontend-example-docker.git
WORKDIR /frontend-example-docker
RUN npm install
RUN npm install -g serve

RUN ls 
ENTRYPOINT API_URL=http://localhost:8000 npm start