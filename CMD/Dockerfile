
# i can give the log format as below, but i will be using below bcause, it is using already created image.

# FROM almalinux:9
# RUN dnf install nginx -y
# CMD ["nginx", "-g", "daemon off;"]

# This is useful when you want to reuse an existing image as the foundation for another image, rather than starting from almalinux:9 again.
FROM run:v1
# In google -> run a command in an nginx container through CMD
CMD ["nginx", "-g", "daemon off;"]