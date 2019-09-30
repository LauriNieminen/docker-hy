FROM ubuntu:16.04

COPY start.sh .
RUN apt-get update && apt-get install -y curl
RUN chmod +x ./start.sh

ENTRYPOINT ["sh", "./start.sh" ]