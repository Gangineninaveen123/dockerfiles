
# i can give the log format as below, but i will be using below bcause, it is using already created image.

# FROM almalinux:9
# RUN dnf install nginx -y
# CMD ["nginx", "-g", "daemon off;"]

# This is useful when you want to reuse an existing image as the foundation for another image, rather than starting from almalinux:9 again.
#Local leka poina parledu, from docker hub repository nunchi pull chestundi, available lo vunte, then run image it will fetch, once docker push done , thorugh username, then only we will get the run full image from below, through docker hub.
FROM gangineninaveen/run:v1
#FROM run:v1

# Just EXPOSE instruction ll tell for public, the port 80 is opened, not having any functionality
EXPOSE 80

# In google -> run a command in an nginx container through CMD
CMD ["nginx", "-g", "daemon off;"]