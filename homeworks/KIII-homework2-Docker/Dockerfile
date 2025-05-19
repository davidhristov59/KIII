FROM ubuntu:18.04

LABEL maintainer="davidhristov10@gmail.com"

RUN apt-get update; apt-get install -y nginx

WORKDIR /var/www/html

RUN echo "Zdravo, sega sme na casot po DevOps" > /var/www/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
