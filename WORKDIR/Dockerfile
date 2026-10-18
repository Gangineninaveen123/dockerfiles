FROM almalinux:9
RUN mkdir /tmp/workdir-demo
# cd command will not work in the Docker., so we will use WORKDIR
# RUN cd /tmp/workdir-demo

# Instead of cd , we will use WORKDIR
WORKDIR /tmp/workdir-demo
RUN pwd
RUN echo "Hello i am in work directory" > hello.txt
CMD ["sleep", "5000"]