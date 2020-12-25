# Alpine test image with nginx

FROM ubuntu:18.04

RUN apt-get update\
 && apt-get install -y nginx

EXPOSE 80 443 8080

CMD ["nginx", "-g", "daemon off;"]

