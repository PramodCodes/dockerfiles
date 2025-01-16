ARG version
FROM almalinux:${version:-8}
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
CMD [ "nginx","-g","daemon off;" ]