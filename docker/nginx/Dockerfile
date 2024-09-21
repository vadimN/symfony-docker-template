FROM nginx:stable

LABEL authors="rezus"

RUN apt update && apt upgrade -y

WORKDIR /var/www/html

CMD ["nginx", "-g", "daemon off;"]