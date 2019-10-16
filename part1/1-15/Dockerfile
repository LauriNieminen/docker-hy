FROM node

RUN apt-get update && apt-get install -y git
RUN git clone https://github.com/LauriNieminen/nipsu-app.git

WORKDIR /nipsu-app/backend

RUN npm install

EXPOSE 3001

ENTRYPOINT [ "npm", "run", "watch" ]