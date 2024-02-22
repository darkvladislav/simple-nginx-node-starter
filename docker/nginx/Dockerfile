FROM nginx:latest

COPY conf/* /etc/nginx/
COPY conf/conf.d/* /etc/nginx/conf.d/

WORKDIR /etc/nginx

EXPOSE 80

ENTRYPOINT ["nginx", "-g", "daemon off;"]
