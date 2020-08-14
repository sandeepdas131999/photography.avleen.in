FROM ubuntu
RUN apt-get update
RUN apt-get install nginx -y
COPY . /var/www/html/
COPY start.sh /start.sh
CMD ["/bin/bash" , "/start.sh"]
