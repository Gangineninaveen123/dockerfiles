FROM almalinux:9
#i can write n number of run commands
RUN dnf install nginx -y
# removing default content in /usr/share/nginx/html/index.html
RUN rm -rf /usr/share/nginx/html/index.html

ADD https://raw.githubusercontent.com/daws-84s/dockerfiles/refs/heads/main/COPY/qi/index.html /usr/share/nginx/html/index.html

#starting the nginx server in container
# daemon off -> means foreground lo run cheyamani
CMD ["nginx", "-g", "daemon off;"]