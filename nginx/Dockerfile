FROM nginx:latest
LABEL mainteiner="frostdimonlex@gmail.com"
WORKDIR usr/share/nginx/html
ARG defname
ARG defage
ENV NAME=$defname
ENV AGE=$defage
ADD ./script.sh ./
RUN chmod a+x ./script.sh
RUN ./script.sh