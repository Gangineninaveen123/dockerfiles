FROM almalinux:9
#i can write n number of run commands
RUN dnf install nginx -y
# removing default content in /usr/share/nginx/html/index.html
RUN rm -rf /usr/share/nginx/html/index.html

#1) add instruction taking from internet
ADD https://raw.githubusercontent.com/daws-84s/dockerfiles/refs/heads/main/COPY/qi/index.html /usr/share/nginx/html/index.html
# giving read access, add instruction taking from internet, but not able to read, so give rread access, to veiw in browser.
RUN chmod +r /usr/share/nginx/html/index.html

#2) untar[unzip] the tar file into container
ADD sample-2.tar /tmp/
# daemon off -> means foreground lo run cheyamani
CMD ["nginx", "-g", "daemon off;"]