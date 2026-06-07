FROM almalinux:8
#CMD ["sleep", "infinity"]d:\Download\frontend
RUN dnf -y update && dnf -y install nginx -y

RUN rm -rf /usr/share/nginx/html/*
COPY . /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]