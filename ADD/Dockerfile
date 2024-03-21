FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/bhanutejan/shellscripting/master/01_firstprog.sh /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]
