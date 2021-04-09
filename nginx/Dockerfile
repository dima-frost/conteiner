FROM nginx:latest
LABEL mainteiner="frostdimonlex@gmail.com"
WORKDIR usr/share/nginx/html
ARG NAME
ARG STATUS
RUN rm index.html && touch index.html && echo "My name is ${NAME} and my status is ${STATUS} ." > index.html