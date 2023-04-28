FROM debian
RUN apt update && apt install -y apache2 php libapache2-mod-php
EXPOSE 80
WORKDIR /app
CMD apachectl -D FOREGROUND