FROM nginx
RUN apt-get update && apt-get install -y wget
WORKDIR /usr/share/nginx/html/
RUN wget -O image.png http://lorempixel.com/300/200/animals/
