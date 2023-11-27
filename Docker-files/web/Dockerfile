FROM nginx
LABEL "project"="container"
LABEL "Author"="Benjamin"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf