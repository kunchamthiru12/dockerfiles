FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBuILD index.html  /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]