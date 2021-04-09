FROM httpd:latest
LABEL mainteiner="frostdimonlex@gmail.com"
WORKDIR /usr/local/apache2/htdocs
ADD index.html  ./
ADD ./script.sh ./
RUN chmod 110 ./script.sh
CMD ./script.sh

