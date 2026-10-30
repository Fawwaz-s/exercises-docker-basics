FROM ubuntu:24.04

WORKDIR /app

COPY script.sh . 

RUN apt-get update 

RUN apt-get install -y curl

CMD ["./script.sh"]



