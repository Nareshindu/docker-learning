FROM almalinux:9
RUN dnf install nginx -y
ADD https://github.com/Nareshindu/docker-learning /tmp
ADD sample-1.tar /tmp
ADD dwsample-tar-gz.tar.gz /tmp
CMD ["nginx", "-g", "daemon off;"]