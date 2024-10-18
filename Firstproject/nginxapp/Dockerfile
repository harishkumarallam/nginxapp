ARG NGINX_VERSION=latest
FROM nginx:${NGINX_VERSION}
ADD index.html /usr/share/nginx/html/index.html
WORKDIR ["nginx","-g","deamon off"]
EXPOSE 80
LABEL description="harish"
ENV APP_VERSION=1.0

