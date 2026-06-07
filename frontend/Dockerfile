FROM nginx:1.24.0-alpine3.17-slim
#CMD ["sleep", "infinity"]d:\Download\frontend
RUN dnf -y update && dnf -y install nginx -y

RUN rm -rf /usr/share/nginx/html/*
COPY ./index.html /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]