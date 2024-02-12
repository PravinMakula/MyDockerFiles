FROM almalinux
RUN yum install nginx -y
RUN rm /usr/share/nginx/html/index.html
COPY q1 /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]