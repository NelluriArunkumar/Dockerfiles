FROM almalinux:9
RUN dnf install nginx -y
RUN mkdir /tmp/workdir-demo
#RUN cd /tmp/workdir-demo Here cd don't work
WORKDIR /tmp/workdir-demo
RUN pwd
RUN echo "Hello Docker" >> hello.txt
CMD ["sleep", "1000"]