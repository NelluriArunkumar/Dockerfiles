FROM almalinux:9
RUN dnf install nginx -y
RUN rm-rf /usr/share/nginx/html/index.html
ADD https://github.com/NelluriArunkumar/ShellPractice/blob/main/01-hello-world.sh /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off"]
